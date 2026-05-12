# 불레방아 공식 웹사이트

## 배포 방법 (딱 3단계)

### 1. GitHub 저장소 만들기
- github.com 접속 → New repository
- Repository name: `bullebanga`
- Public 선택 → Create repository

### 2. 파일 올리기
이 ZIP 안의 파일 3개를 저장소에 업로드:
- `index.html`
- `갈비데이_특허증.jpg`
- `CNAME`

### 3. GitHub Pages 켜기
- 저장소 → Settings → Pages
- Source: **Deploy from a branch**
- Branch: **main** / root → Save
- 잠깐 기다리면 bullebanga.com 자동 연결됨

---

## 가비아 DNS 설정 (복붙하세요)

가비아 로그인 → 도메인 관리 → bullebanga.com → DNS 설정

| 타입  | 호스트 | 값                    | TTL  |
|-------|--------|-----------------------|------|
| A     | @      | 185.199.108.153       | 600  |
| A     | @      | 185.199.109.153       | 600  |
| A     | @      | 185.199.110.153       | 600  |
| A     | @      | 185.199.111.153       | 600  |
| CNAME | www    | machojang-create.github.io | 600 |

DNS 반영 최대 24시간 (보통 1~2시간)
