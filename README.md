# GitHub Trending TOP 10 (모바일 PWA)

반응형 모바일 화면과 홈 화면 설치(PWA)를 지원합니다.

## 휴대폰에서 사용
1. 이 폴더를 GitHub 저장소의 최상위에 업로드합니다.
2. 저장소 Settings → Pages → Build and deployment → Deploy from a branch → main / root → Save를 선택합니다.
3. 배포된 `https://사용자명.github.io/저장소명/` 주소를 휴대폰 브라우저로 엽니다.
4. Android Chrome: 메뉴(⋮) → 홈 화면에 추가 또는 앱 설치. iPhone Safari: 공유 → 홈 화면에 추가.

**주의:** PWA 설치와 서비스워커는 HTTPS 배포 후 동작합니다. `index.html`을 휴대폰 파일로 직접 열면 설치 기능이 동작하지 않습니다. GitStock 비공식 API가 CORS를 허용하지 않거나 데이터가 없으면 조회가 실패할 수 있습니다. 오프라인에서는 앱 껍데기만 열리며 실시간 순위는 인터넷이 필요합니다.
