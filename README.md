## 🔗 배포 링크

https://taskify-amber-iota.vercel.app/

<br/>
<br/>
<br/>

## 🛠 사용 기술

<div align=center> 
  <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black">
  <img src="https://img.shields.io/badge/next-000000?style=for-the-badge&logo=nextdotjs&logoColor=white">
  <img src="https://img.shields.io/badge/typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">
  <img src="https://img.shields.io/badge/cssmodules-000000?style=for-the-badge&logo=cssmodules&logoColor=white">
  <img src="https://img.shields.io/badge/axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white">
  <img src="https://img.shields.io/badge/eslint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white">
  <img src="https://img.shields.io/badge/prettier-F7B93E?style=for-the-badge&logo=prettier&logoColor=black">
</div>

<br/>
<br/>
<br/>

## 📄 개발 내용

1. 대시보드 관리 및 카드 리스트 (무한 스크롤 구현)
  무한 스크롤 최적화: Intersection Observer API를 사용하여 컬럼별 카드 리스트의 무한 스크롤을 구현.
  UX 개선: rootMargin: 100px 설정을 통해 사용자가 스크롤 끝에 도달하기 전 데이터를 미리 페칭하여 끊김 없는 사용자 경험을 제공.

2. 효율적인 공통 컴포넌트 설계
  Color Picker: 재사용성을 고려하여 Props로 받은 Hex Color를 제어하고, 선택된 값을 콜백 함수로 반환하는 인터페이스를 구축.
  User Avatar: 단일 아바타와 그룹화된 리스트 형태를 모두 지원하도록 모듈화했습니다. 특히 Next.js Image 모듈을 활용해 이미지 최적화를 적용, 로딩 속도를 향상시킴.
  Header Navigation: 레이아웃 패턴을 적용하여 페이지별 네비게이션 바 노출 여부를 유연하게 관리.

3. 탭(Tab) 기반 대시보드 수정 페이지
  Enum 활용: 수정, 멤버 관리, 삭제 등 명확히 구분되는 상태를 Enum으로 관리하여 코드의 가독성과 타입 안정성을 확보.
  상태 관리: 좌측 탭 선택에 따라 우측 컨텐츠 영역이 동적으로 렌더링되는 구조로 설계.
  UX 디테일: 대시보드 삭제 시 setTimeout을 활용하여 즉각적인 리다이렉트 대신 자연스러운 화면 전환 피드백을 제공.

4. 스타일링 및 환경 설정
  CSS Modules: 컴포넌트 기반 스타일링을 위해 CSS Modules를 채택, 클래스 네임 충돌을 방지하고 스타일 캡슐화.

<br/>
<br/>
<br/>

## 랜딩 페이지

<img width="1816" height="1092" alt="taskify" src="https://github.com/user-attachments/assets/7ea44718-b27f-459b-8cf6-2b6cb50ffba9" />
