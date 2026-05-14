# beyond45rpm — Gallery

3D printed objects for vinyl lovers. 다크톤 미니멀 갤러리 사이트.

---

## 🚀 GitHub Pages 배포 가이드 (5분)

### 1단계: 새 레포지토리 만들기
1. github.com 로그인 → 우측 상단 `+` → **New repository**
2. Repository name: `beyond45rpm`
3. **Public** 선택
4. **Create repository**

### 2단계: 파일 업로드
**웹에서 드래그앤드롭 (제일 쉬움):**
1. 새 레포 페이지에서 **"uploading an existing file"** 링크 클릭
2. 폴더 안 파일들 전부 드래그 (`index.html` + `images/` 폴더)
3. **Commit changes**

**또는 git 명령어:**
```bash
cd beyond45rpm-site
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/본인username/beyond45rpm.git
git push -u origin main
```

### 3단계: GitHub Pages 활성화
1. 레포 → **Settings** → **Pages**
2. Source: **Deploy from a branch** / Branch: **main** / **/ (root)**
3. **Save**
4. 1~2분 후 URL 생성됨: `https://본인username.github.io/beyond45rpm`

---

## 📸 이미지 추가하기

이미지 없으면 placeholder가 나오니 꼭 추가하세요.

### Etsy에서 이미지 다운로드
1. Etsy 샵 들어가서 각 제품 클릭
2. 메인 이미지 우클릭 → **이미지 저장**

### `images/` 폴더에 아래 파일명으로 저장

| 파일명 | 어떤 제품 |
|--------|----------|
| `vinyl-box-clear.jpg` | Clear Translucent Vinyl Box ($75) |
| `vinyl-box-yellow.jpg` | Yellow Vinyl Box ($68) |
| `45rpm-adapters.jpg` | Fast Food 45RPM Adapters ($30) |
| `heart-adore-adapters.jpg` | Heart & Adore 45RPM Adapters ($45) |

**팁:** 정사각형 1:1 비율이 가장 깔끔하게 보여요. 800x800px ~ 1200x1200px 추천.
**다크톤이라** 사진이 밝고 깨끗할수록 갤러리에서 잘 떠 보여요.

---

## 🎨 사이트 디자인 요소

- **컬러**: 거의 블랙(#0a0a0a) 배경 + 베이지/골드 액센트(#d4b896)
- **타이포**: Fraunces (이탤릭 세리프, 우아한 헤드라인) + JetBrains Mono (모노스페이스, 모던한 라벨)
- **인터랙션**: 호버 시 이미지 확대 + 정보 슬라이드업
- **그레인 텍스처**: 미세한 노이즈 오버레이로 필름 느낌
- **모바일**: 자동으로 정보 표시 (호버 없어서)

---

## ✏️ 자주 수정하는 부분

`index.html` 열어서:

### 헤드라인 변경
```html
<h1>Objects for<br>those who <em>spin</em>.</h1>
```

### 인스타 주소 변경
`https://www.instagram.com/ssumwear` 부분 → 본인 인스타로 교체

### 액센트 색상 변경
파일 맨 위 `:root`에서:
```css
--accent: #d4b896;  /* 베이지/골드 */
```
다른 추천 색상:
- `#c08552` — 카퍼/브론즈
- `#a8b5a0` — 세이지 그린
- `#e8e8e8` — 순수 화이트
- `#9b8cb5` — 라일락 그레이

---

## 🎯 레니게이드 신청 폼에 넣을 링크

배포 후:
- **Link to images of your work**: `https://본인username.github.io/beyond45rpm`
- **Link to your Instagram**: 본인 인스타 URL

수정 필요하면 언제든지 알려주세요!
