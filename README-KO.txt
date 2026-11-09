구슬 뽑기 Windows EXE 빌드

1. 이 ZIP 파일의 압축을 풉니다.
2. GitHub에서 새 저장소를 만들거나 기존 guselpick 저장소를 엽니다.
3. 이 ZIP 안의 파일과 폴더를 저장소 최상위에 업로드합니다.
   - package.json
   - main.js
   - .github/workflows/build-windows.yml
4. Commit changes를 누릅니다.
5. GitHub 저장소의 Actions 탭으로 이동합니다.
6. "Build Windows EXE" 작업이 실행되는지 확인합니다.
7. 작업이 완료되면 실행 결과 페이지 아래 Artifacts에서
   guselpick-windows-exe 를 다운로드합니다.
8. 다운로드한 ZIP을 풀면 "구슬 뽑기 Setup 1.0.0.exe" 설치 파일이 있습니다.

참고:
- Windows x64용 설치 파일을 만듭니다.
- 앱은 인터넷에 연결해 원래 사이트를 표시합니다.
- 사이트의 기능과 이미지/참여자 데이터 저장 방식은 원래 웹사이트와 같습니다.
- 사이트가 업데이트되면 앱에도 새 내용이 자동으로 표시됩니다.
