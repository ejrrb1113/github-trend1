ZIP을 풀고 **안의 모든 파일과 .github/workflows/trending.yml**을 저장소 최상위에 업로드합니다. .github는 숨김 폴더일 수 있으므로 PC에서 업로드하는 편이 쉽습니다.
GitHub 저장소 Settings → Actions → General → Workflow permissions 에서 Read and write permissions 설정 후 저장합니다. 조직 정책에 따라 제한될 수 있습니다.
Actions → Collect trending → Run workflow 를 실행합니다.
실행 완료 후 저장소에 data/latest.json과 data/YYYY-MM-DD.json이 생성되었는지 확인합니다.
Pages가 새로 배포되면 새로고침합니다. 이전 PWA 캐시가 남아 있다면 사이트 데이터를 삭제 후 재접속합니다.
주의
과거 데이터는 자동으로 복원되지 않습니다. 수집을 시작한 날부터 쌓입니다. 지난주 데이터가 없으면 표시하지 않습니다.
GitHub Trending은 GitHub 공식 랭킹 API가 아니며 페이지 구조가 바뀌면 수집기가 실패할 수 있습니다.
GitHub Actions 일정 실행은 지연될 수 있습니다.
수집 실패 시 Actions 실행 로그에서 오류를 확인합니다.
