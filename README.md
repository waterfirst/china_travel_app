https://polite-dodol-9c8a9a.netlify.app/

# 🌏 중국 여행 가이드 앱 만들기 (Claude AI & Bolt.ai)

## 프로젝트 소개
Claude AI와 Bolt.ai를 활용하여 중국 여행객을 위한 모바일 가이드 앱을 제작하는 프로젝트입니다. React와 Tailwind CSS를 기반으로 제작되었으며, 실제 여행 일정과 정보를 바탕으로 구현되었습니다.

## 주요 기능
- 📍 **네비게이션**
  - 관광지 정보 및 위치 확인
  - 길찾기 및 지도 보기
  - 주요 관광지 상세 정보

- 🚆 **교통 정보**
  - 항공/기차 예약 정보
  - 실시간 운행 상태
  - 교통편 상세 정보

- 🏨 **호텔 정보**
  - 예약된 숙소 정보
  - 체크인/아웃 시간
  - 호텔 편의시설 및 연락처

- 💬 **중국어 회화**
  - 상황별 필수 회화
  - 한자/병음/한글 표시
  - 발음 듣기 기능

- 💱 **환율 계산**
  - 실시간 환율 정보
  - 원-위안 환율 계산
  - 빠른 환율 계산 기능

- 📅 **일정표**
  - 일자별 여행 일정
  - 시간대별 활동 계획
  - 카테고리별 일정 구분

## 기술 스택
- React
- Tailwind CSS
- Lucide React Icons
- Google Maps API (예정)

## 개발 도구
- Claude AI: 코드 생성 및 최적화
- Bolt.ai: UI/UX 디자인 및 컴포넌트 구현
- GitHub: 버전 관리
- VS Code: 코드 편집

## 프로젝트 구조
```
src/
├── components/
│   ├── Navigation.js
│   ├── Transport.js
│   ├── Hotel.js
│   ├── Language.js
│   ├── Currency.js
│   └── Schedule.js
├── data/
│   └── travelData.js
├── styles/
│   └── tailwind.css
└── App.js
```

## 설치 및 실행 방법
1. 레포지토리 클론
```bash
git clone https://github.com/yourusername/china-travel-guide.git
```

2. 의존성 설치
```bash
cd china-travel-guide
npm install
```

3. 개발 서버 실행
```bash
npm start
```

## 데모
[라이브 데모 링크] (추가 예정)

## 스크린샷
![앱 메인 화면](screenshots/main.png)
(스크린샷 추가 예정)

## 향후 계획
- [ ] Google Maps API 연동
- [ ] 실시간 환율 API 연동
- [ ] 음성 인식 기능 추가
- [ ] 오프라인 모드 지원
- [ ] 다국어 지원

## 기여 방법
1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 라이선스
MIT License - 자세한 내용은 [LICENSE](LICENSE) 파일을 참조하세요.

## 제작자
- [@yourgithub](https://github.com/yourgithub) - 프로젝트 기획 및 개발
- Claude AI - 코드 생성 및 최적화
- Bolt.ai - UI/UX 디자인 지원

## 감사의 말
- Anthropic의 Claude AI
- Bolt.ai 팀
- React 커뮤니티
- Tailwind CSS 팀

---
이 프로젝트는 실제 중국 여행 경험을 바탕으로 제작되었으며, AI 도구를 활용한 개발 과정을 공유하고자 합니다.
