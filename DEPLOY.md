# 테슬라 홈페이지 배포

아우디 원본 HTML/CSS/JS 구조를 유지한 테슬라 전용 수정본입니다.

1. ZIP 압축을 해제하고 모든 파일과 `assets/`, `functions/` 폴더를 GitHub 새 저장소에 업로드합니다.
2. Cloudflare Pages에서 GitHub 저장소 연결, 프레임워크 None, 빌드 명령 비움, 출력 디렉터리 `.`로 배포합니다.
3. 배포 주소 확정 후 `python prepare_domain.py https://실제주소.pages.dev`를 실행하고 변경된 index.html/robots.txt/sitemap.xml을 업로드합니다.
4. `/assets/brand.jpg`, `/favicon.ico`, `/api/latest-posts` 접속을 확인합니다. RSS는 네이버 접근 제한에 따라 실패할 수 있습니다.
5. 네이버 서치어드바이저·구글 서치콘솔에 사이트맵 제출. 검색 대표사진 노출은 검색엔진 재량입니다.

※ 사례 차량 사진은 제공되지 않아 텍스트 그래픽으로 대체했습니다. 일부 사례의 차량가 원본 견적 확인 필요.
