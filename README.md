# 교육사회 (CH268-B1) 과목소개 페이지

연성대학교 유아교육과 「교육사회」(CH268-B1) 소개 페이지. CSS·JS·강의계획서 PDF가 모두 `index.html` 하나에 내장된 정적 페이지입니다.

## GitHub Pages 배포 방법

1. 이 폴더 내용을 GitHub 저장소에 푸시합니다.
   ```bash
   git remote add origin <저장소 URL>
   git push -u origin main
   ```
2. 저장소 **Settings → Pages**에서 Source를 `Deploy from a branch`로, Branch를 `main` / `(root)`로 설정합니다.
3. 몇 분 뒤 `https://<계정명>.github.io/<저장소명>/` 에서 확인할 수 있습니다.

## 배포 전 확인할 것

- `index.html` 안의 `VIDEO.youtubeId`가 비어 있으면 "준비 중" 상태로 표시됩니다. 실제 소개 영상 업로드 후 채워주세요.
- 「수강생 통계와 후기」 섹션은 예시 데이터입니다. 실제 강의평가 결과로 교체 후 `예시 데이터` 배지도 함께 제거해주세요.
- `files/syllabus-ch268-b1-2026-2.pdf`는 페이지 내 다운로드 링크의 대비용 사본입니다. 실제 강의계획서는 `index.html` 안에 base64로 내장되어 있어 이 파일이 없어도 열람 기능은 동작합니다.
