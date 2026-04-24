# StockBoard Pro 📈

실시간 시장 데이터와 기업 재무 지표를 한눈에 모니터링할 수 있는 전문가용 주식 현황판 대시보드입니다.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![React](https://img.shields.io/badge/React-18.x-61dafb.svg)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.x-38b2ac.svg)

## ✨ 주요 기능

- **실시간 주가 모니터링**: KOSPI 상위 종목들의 최신 시세와 등락률을 실시간으로 확인 (2026.04.24 기준 데이터 반영).
- **인터랙티브 차트**: ApexCharts를 활용하여 1D, 1W, 1M 등 기간별 주가 추이를 미려한 곡선 그래프로 제공.
- **재무 100선 데이터**: 시가총액 상위 기업들의 핵심 재무 지표(PER, PBR, ROE 등)를 비교 분석 가능한 테이블.
- **스마트 검색**: 종목명 또는 종목 코드로 즉시 필터링 가능한 고성능 검색 기능.
- **관심 종목(Watchlist)**: 나만의 관심 종목을 추가하여 실시간으로 가격 변동을 감시.
- **다크 모드 최적화**: 전문가용 대시보드에 최적화된 고품격 다크 테마 및 반응형 레이아웃.

## 🚀 시작하기

이 프로젝트는 별도의 빌드 과정 없이 웹 브라우저에서 즉시 실행 가능합니다.

1. 이 저장소를 클론합니다:
   ```bash
   git clone https://github.com/jeh3077/stock.git
   ```
2. `index.html` 파일을 크롬 등 브라우저로 엽니다.
3. 로컬 서버(localhost) 환경에서 실행하려면:
   ```bash
   python -m http.server 3001
   ```
   이후 `http://localhost:3001`로 접속하세요.

## 🛠 기술 스택

- **Frontend**: React (18.x), Tailwind CSS
- **Charts**: ApexCharts
- **Icons**: Lucide Icons
- **Data Source**: Google Finance & Market Simulation Logic

## 📄 라이선스

이 프로젝트는 MIT 라이선스를 따릅니다.
