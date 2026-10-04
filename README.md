[README.md](https://github.com/user-attachments/files/33027418/README.md)
# POP&CON 홈페이지

- `index.html` : 홈페이지 전체 (HTML/CSS/JS 포함, 빌드 과정 불필요)
- `images/` : 사이트에 쓰이는 이미지 전부 (로고, 히어로 배경, 사진 등 10장). 반드시 `index.html`과 같은 위치에 함께 올려야 이미지가 보입니다

## 1. GitHub에 올리기
1. github.com 로그인 → 오른쪽 위 `+` → `New repository`
2. Repository name 입력 (예: `MY-SITE`), `Public` 선택 → `Create repository`
3. 새 저장소 화면에서 `uploading an existing file` 링크 클릭
4. `index.html` 파일과 `images` 폴더를 함께 끌어다 놓기 (README.md는 올려도 되고 안 올려도 됩니다)
5. 아래 `Commit changes` 클릭

## 2. Vercel에 무료로 배포하기
1. vercel.com 접속 → `Sign Up` → `Continue with GitHub`로 가입/로그인 (Hobby 플랜 = 무료)
2. `Add New...` → `Project` 클릭
3. 방금 만든 GitHub 저장소 옆 `Import` 클릭 (안 보이면 `Adjust GitHub App Permissions`에서 저장소 접근 허용)
4. 설정은 건드리지 않고 그대로 둡니다
   - Application Preset: Other
   - Root Directory: ./
5. `Deploy` 클릭 → 약 1분 후 `xxxx.vercel.app` 주소로 사이트가 열립니다

## 3. 내용 수정하기
- GitHub 저장소에서 `index.html`을 열고 연필 아이콘으로 수정 후 `Commit changes`
- 또는 수정된 새 `index.html`을 같은 이름으로 다시 업로드(덮어쓰기)
- 저장하면 Vercel이 자동으로 다시 배포합니다 (1분 내외)

## 참고
- 페이지에서 글자를 직접 클릭해 고치는 편집 모드는 Claude 안에서만 작동합니다. Vercel 사이트에서는 편집 버튼이 보이지 않습니다.
