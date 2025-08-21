<img src="https://i.ibb.co/TB50Q24t/blocky-logo.png" alt="Blocky 로고" width="400"/>

# Blocky

> Blockly와 React를 활용한 **웹 기반 프론트엔드 교육 플랫폼**  
> 블록을 조합하며 HTML/CSS를 직관적으로 배우고, 곧바로 코드로 확인할 수 있습니다.



## 📽️ 소개 영상
👉 [시연 영상 보러가기](https://youtu.be/M5pYUKHvOOw)  


## 📖 프로젝트 소개
BLOCKY는 프론트엔드 입문자를 위해, 블록 코딩을 통해 화면 스타일링을 직관적으로 배우고 곧바로 코드로 확인할 수 있는 학습 플랫폼입니다.


## 🚀 주요 기능
- ✔️ 블록 조립을 통한 HTML/CSS 직관적 학습
- ✔️ 단계별 미션 (자유 모드 / 미션 수행 모드)
- ✔️ 실시간 코드 미리보기 & 자동 변환 (Blockly → JSX → HTML)
- ✔️ 채점 및 즉시 피드백 기능
- ✔️ UI/스타일/레이아웃 전용 블록 제공


## 🎯 학습 대상
- 웹 개발 입문자
- 시각적 학습을 선호하는 학생
- 블록 코딩으로 HTML/CSS를 재미있게 배우고 싶은 누구나


## 🛠️ 기술 스택
- **Frontend**: React (UI 구성), Blockly (블록 코딩 UI)
- **Backend**: SpringBoot, MySQL
- **Language**: JavaScript (ES6+), JSX
- **개발 도구**: GitHub (버전 관리), Visual Studio Code (IDE), IntelliJ iDEA
- **배포 환경**: 브라우저 실행(Web 기반 플랫폼), S3 (프론트엔드 배포), AWS EC2 (서버 확장 고려)



## 📦 설치 & 실행

# 패키지 설치
npm install

# 로컬 실행
npm start

접속 주소: [Blocky 데모](http://blocky-web.s3-website.ap-northeast-2.amazonaws.com/)


## 🏗️ 시스템 아키텍처 & 학습 모드
BLOCKY는 **Blockly.js**를 확장하여 UI/스타일/레이아웃 전용 블록을 직접 설계했습니다.  
<img width="2197" height="1117" alt="전체 구조도" src="https://github.com/user-attachments/assets/b940a5ca-1d4b-41a0-b12e-67bb5aaeb892" />


- 블록 → XML 변환 → JSX 파서 → HTML 코드 미리보기  
- 자유 모드: 제약 없는 실습, 창의적 블록 조합
- 미션 모드: 문제 제시 → 블록 조립 → 자동 채점 및 피드백 제공

<img width="2972" height="2243" alt="전체 렌더링 구조" src="https://github.com/user-attachments/assets/6f718c48-c221-4aa9-9430-719681e9991b" />


## 🌟 기대 효과 및 활용
- 블록 코딩으로 프론트엔드 학습 진입 장벽을 낮춤
- 즉시 코드 확인을 통해 CSS 스타일링/화면 구성을 직관적으로 이해 가능  
- 자유 실습 + 문제 해결형 학습을 동시에 경험할 수 있음
- 교육 현장 교보재, 온라인 코딩 교육 서비스 등으로 확장 가능


## 🔮 향후 계획
- JavaScript 이벤트 처리 블록 추가
- 반응형 레이아웃, 다양한 UI 컴포넌트 확장 
- AI 튜터 기능: 코드 오류 수정·개선 피드백 제
- 사용자 관리·저장 기능 강화 (AWS EC2)


## 👥 팀원

| <a href="https://github.com/hana03030"><img src="https://github.com/hana03030.png" width="120px;" alt="이주현"/></a> | <a href="https://github.com/chunys"><img src="https://github.com/chunys.png" width="120px;" alt="천유석"/></a> | <a href="https://github.com/ye-eun-min201"><img src="https://github.com/ye-eun-min201.png" width="120px;" alt="임예은"/></a> | <a href="https://github.com/mimolulu"><img src="https://github.com/mimolulu.png" width="120px;" alt="성유빈"/></a> |
|:---:|:---:|:---:|:---:|
| 이주현 <br/>[@hana03030](https://github.com/hana03030) | 천유석 <br/>[@chunys](https://github.com/chunys) | 임예은 <br/>[@ye-eun-min201](https://github.com/ye-eun-min201) | 성유빈 <br/>[@mimolulu](https://github.com/mimolulu) |


## 📜 라이선스
MIT License

Copyright (c) 2025 Blocky Team

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

