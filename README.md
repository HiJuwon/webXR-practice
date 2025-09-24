# 🕹️ webXR-practice
A-frame, webXR device API를 활용하여 웹 기반의 멀티디바이스 적응형 VR 제작을 테스트해보는 레포지토리

---

## 💻 Tech Stack
웹 개발은 **React + TypeScript + Vite**를 기본으로 하되, 아래의 기술을 활용한다.
<br> 필요 시 aframe-react 등 기타 라이브러리를 추가 사용한다.

- **A-Frame** `Main Framework`
  - VR 체험 뷰 구성
  - VR 핸드트랙킹/컨트롤러 입력 지원
  - VR내 사운드 기능 지원
 
- **WebXR Device API**
  - HMD의 핸드트래킹, VR 모드 진입, local floor 기준 제공
 
---

## 🎯 Goal
- HMD(Meta Quest 3s)와 웹 환경에서 동시 접속 가능한 web기반 VR 구현
- Meta Quest 3s의 핸드트래킹과 웹의 키보드/마우스 컨트롤 조작을 모두 인식 가능하도록 구현
- VR 내에 측정이 필요한 데이터를 심고 해당 데이터를 추출하여 Protopie 커넥트용으로 데이터 추출 -> GUI 프로토타입 인터랙션과 연결 가능하도록
