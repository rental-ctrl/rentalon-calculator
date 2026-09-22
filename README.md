# 렌탈ON V26 - GitHub Pages 업로드용

1. GitHub 저장소에서 Add file -> Upload files
2. `index.html` 업로드
3. Settings -> Pages -> Deploy from a branch
4. Branch: main / Folder: /(root) 선택
5. Save 후 생성된 Pages 주소 접속

현재 포함:
- 반응형 고객 화면
- 제조사/차량 선택
- 예산 상담
- 상담 신청
- 본인인증 데모
- 브라우저 localStorage 상담 DB
- 관리자 대시보드 및 상담 상태 변경

실제 운영 전:
- 본인인증 API
- 서버 DB/Supabase/Firebase 등
- 관리자 로그인
- 개인정보처리방침 및 동의 이력
- SMS/알림톡
- 실제 차량 데이터 관리
- 렌터카사 견적 API/제휴 연동

주의: GitHub Pages만으로는 여러 기기에서 공유되는 고객 DB를 만들 수 없습니다. 현재 DB는 테스트용으로 해당 브라우저에만 저장됩니다.
