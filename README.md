# 한끼 기록장

매일 식단 사진을 찍어 폰에만 저장하는 개인 식단 기록 앱. 서버·로그인 없음.

## 배포 (GitHub Pages)
1. 기존 `hankki` 저장소에 이 폴더의 파일을 전부 업로드 (같은 이름은 덮어쓰기)
2. Settings > Pages > Branch: main / (root)
3. 1~2분 뒤 `https://<아이디>.github.io/hankki/`

## 파일
- index.html : 앱 본체
- bg.js : 음식 배경 지우기 도구 (@imgly/background-removal 1.5.8 묶음). 모델 파일은 처음 사용할 때 staticimgly.com에서 받아 폰에 보관
- manifest.json, icon-*.png, apple-touch-icon.png : 홈 화면 아이콘
- sw.js : 오프라인용 캐시. 파일을 고친 뒤에는 C 값의 숫자를 올려 주세요
