# 김민준 — Academic personal website

Website: https://kamelopard.github.io/

## 수정 방법 (GitHub 웹 편집기)

1. 저장소에서 `index.html`을 열고 오른쪽 위 연필 아이콘(Edit this file)을 누릅니다.
2. 파일 안의 `수정 1`~`수정 8` 주석을 기준으로 내용을 바꿉니다.
   1. 프로필: 영문 이름, 이메일, 사진 경로
   2. 메인 소개와 연구 관심 분야
   3. 논문(Journals / International Conferences / Domestic Conferences), 특허, 참여과제
3. 오른쪽 위 **Commit changes**를 눌러 `main` 브랜치에 저장합니다. 1~2분 뒤 사이트에 반영됩니다.

## 이미지 바꾸기

1. `assets` 폴더에서 **Add file → Upload files**로 이미지를 올립니다.
2. `index.html`에서 해당 이미지의 `src` 경로를 새 파일 이름으로 바꿉니다.
   1. 프로필 사진: `assets/profile.jpg`
   2. 논문 이미지: 학술대회 포스터 `assets/conf-연도-학회-시즌.jpg`
   3. 과제 이미지: 전문기관 로고 `assets/logo-nrf.png`, `assets/logo-kiat.png`

## 참고

1. 논문 항목 중 `data-featured`가 붙은 앞의 두 개가 홈 화면 "대표 연구"에 표시됩니다.
2. 논문 분류에 항목을 추가하면 그 분류의 `empty-state` 문단(“등록된 … 없습니다”)을 지웁니다.
3. 저장소 쓰기 권한이 있는 계정만 수정할 수 있습니다.
