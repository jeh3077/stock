# 📈 StockBoard Pro: Next-Generation Market Dashboard

**StockBoard Pro**는 실시간 시장 데이터 시각화와 기업 재무 지표 분석에 최적화된 고성능 주식 모니터링 대시보드입니다. React와 가상 DOM 기술을 활용하여 복잡한 금융 데이터를 끊김 없이 매끄럽게 처리하며, 전문가용 다크 테마 인터페이스를 통해 최상의 사용자 경험을 제공합니다.

---

## ✨ 핵심 기능 (Core Features)

### 1. 실시간 데이터 엔진 (Real-time Market Data)
- **정밀 시세 반영**: 2026년 4월 24일 기준, 실제 시장 종가와 등락률을 반영한 신뢰도 높은 기초 데이터.
- **실시간 데이터 로직**: 전일 종가(`basePrice`) 기반의 정밀한 등락률 계산 공식을 통해 시장 논리에 부합하는 데이터 시각화.
- **KOSPI & 환율 동기화**: 상단 헤더를 통해 주요 시장 지수와 원/달러 환율 정보를 실시간으로 트래킹.

### 2. 인터랙티브 데이터 시각화 (Interactive Visualization)
- **Multi-Timeframe Charts**: `ApexCharts` 엔진을 탑재하여 1D(일), 1W(주), 1M(월) 등 다양한 기간별 주가 추이 분석.
- **Dynamic Tooltips**: 마우스 호버 시에만 세부 주가가 노출되는 깔끔한 UI 및 데이터 레이블 최적화.
- **Smooth Animations**: 데이터 전환 시 적용되는 부드러운 애니메이션 효과로 가독성 향상.

### 3. 지능형 종목 관리 (Smart Stock Management)
- **Fast Search Engine**: 초성 검색 및 종목 코드를 지원하는 즉각적인 필터링 시스템.
- **Custom Watchlist**: 사이드바 기반의 관심 종목 관리 기능을 통해 중요 종목의 변동성을 실시간 감시.
- **Financial Board**: PER, PBR, ROE 등 핵심 재무 지표를 시가총액 순위와 함께 제공하여 기업 펀더멘털 분석 지원.

---

## 🛠 기술 스택 (Technical Stack)

| 구분 | 기술 | 상세 설명 |
| :--- | :--- | :--- |
| **Library** | **React 18** | 컴포넌트 기반 아키텍처 및 선언적 UI 구현 |
| **Styling** | **Tailwind CSS** | 유틸리티 퍼스트 프레임워크 기반의 반응형 레이아웃 |
| **Charts** | **ApexCharts** | 고성능 SVG 기반 인터랙티브 금융 차트 구현 |
| **Icons** | **Lucide Icons** | 현대적이고 깔끔한 벡터 아이콘 세트 |
| **Compiler** | **Babel** | 별도의 빌드 도구 없이 브라우저에서 JSX 실행 지원 |

---

## 🚀 빠른 시작 (Quick Start)

본 프로젝트는 **Zero-Configuration** 지향으로, 별도의 의존성 설치 없이 즉시 실행 가능합니다.

### 1. 저장소 클론
```bash
git clone https://github.com/jeh3077/stock.git
cd stock
```

### 2. 로컬 서버 가동 (권장)
웹 브라우저의 보안 정책(CORS) 문제를 방지하기 위해 로컬 서버 환경에서 실행하는 것을 권장합니다.
```bash
# Python 이용 시
python -m http.server 3001

# Node.js 이용 시
npx serve -l 3001
```
이후 브라우저에서 `http://localhost:3001`로 접속하세요.

---

## 🏗 프로젝트 구조 (Architecture)

```text
stock/
├── index.html          # 메인 React 애플리케이션 (주식 현황판)
├── 주식현황판.txt      # 제품 요구사항 정의서 (PRD)
├── README.md           # 프로젝트 문서
└── .gitignore          # 로컬 전용 파일(로또 생성기 등) 제외 설정
```

---

## 🗺 향후 로드맵 (Future Roadmap)

- [ ] **실제 API 연동**: 공공데이터포털 또는 증권사 Open API를 통한 100% 실시간 데이터 동기화.
- [ ] **다크/라이트 모드**: 사용자 취향에 따른 테마 전환 기능 고도화.
- [ ] **포트폴리오 관리**: 사용자의 보유 주식 및 수익률 계산 기능 추가.
- [ ] **PWA 지원**: 모바일 앱처럼 사용할 수 있는 프로그레시브 웹 앱 기능 도입.

---

## 📄 라이선스 (License)

Copyright © 2026 [jeh3077](https://github.com/jeh3077).
This project is [MIT](https://opensource.org/licenses/MIT) licensed.
