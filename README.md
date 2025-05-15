# HiddenNode 프로젝트

> **잊힌 이름, 숨겨진 기록**  
> 판결문 기반 독립운동 인물·사건의 시각화 플랫폼

---

## 🔍 프로젝트 개요

HiddenNode는 일제강점기 **판결문 속 인물·사건·장소 정보를 구조화**하고,  
**지식그래프 기반 시각화**를 통해 잊힌 독립운동 기록을 되살리는 웹 애플리케이션입니다.

- STI(Semantic Table Interpretation)를 활용한 의미 관계 추출
- 시각적 탐색이 가능한 UI 구성
- 독립운동사 데이터 기반 지식그래프 탐색

---

## 🖼️ 메인 화면 구성

| 섹션 | 설명 |
|------|------|
| Hero Section | 배경 이미지 + 탐색 버튼 |
| 판결문 소개 | 판결문의 중요성 설명 |
| 3단계 카드 섹션 | 데이터 정규화 → 지식그래프 → 탐색 방식 소개 |
| 시각화 사례 | 특정 인물의 판결문 기반 탐색 사례 소개 |
| 팀 소개 & 철학 | HiddenNode 팀과 프로젝트 방향성 설명 |
| Stepper Section | 기능 단계별 안내 섹션 |

---

## 🧠 지식그래프 화면 구성

HiddenNode의 지식그래프 화면은 사용자가 **판결문 기반 인물·사건·장소 간 관계를 직관적으로 탐색**할 수 있도록 설계되었습니다.

| 섹션 | 설명 |
|------|------|
| 상단 툴바 | 탐색 기능 버튼 (`리셋`, `확대`, `축소`, `중심 이동` 등) 배치 |
| 시각화 영역 | sigma.js 기반 지식그래프 시각화. 노드 클릭 시 정보 표시 |
| 사이드바 (오른쪽) | 선택한 노드(인물, 사건 등)에 대한 상세 정보 출력 (년도, 설명, 관련 이미지 등) |
| 이미지 하단 버튼 | 그래프 뷰를 조정할 수 있는 `+`, `-` 버튼 (확대/축소) |
| 토글 버튼 | 사이드바를 열고 닫는 toggle 버튼 제공 (화면 집중 모드 지원) |

> 지식그래프 인터페이스는 **반응형**으로 설계되어 데스크탑 및 태블릿 화면에서 최적화된 시각 탐색을 지원합니다.

---

## 🛠️ 기술 스택

- **Next.js (App Router)**
- **Tailwind CSS**
- **Radix UI + ShadCN**
- **Dynamic Import** for SSR control

---

## 🧩 Figma 프로토타입

디자인은 Figma를 기반으로 제작되었습니다.

[🖼️ Figma 프로토타입 보기](https://www.figma.com/design/nUWkq3RUz0uDMKt7DdBsbx/%EB%8F%85%EB%A6%BD%ED%8C%90%EA%B2%B0%EB%AC%B8?node-id=168-412&p=f&t=YUW3n9AmeuGdd019-0)

---

## 📦 GitHub 저장소

- [🔗 HiddenNode 프론트엔드 GitHub 바로가기](https://github.com/dau-J/hidden_node_test.git)

---

## 🚀 배포 및 실행 방법

```bash
git clone https://github.com/Donga-SW/frontend.git
cd hidden-node
npm install
npm run dev
```

# requirements
-----------------------------------------------------------------------
npm install next react react-dom --legacy-peer-deps



