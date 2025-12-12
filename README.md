# TARGETKOREA Assets Repository

TARGETKOREA 리포트 자동화 시스템에서 사용되는 로고 및 에셋을 관리하는 레포지토리입니다.

## 📁 구조

```
targetkorea-assets/
├── logos/              # 플랫폼 로고 이미지
│   ├── kb-card.png
│   ├── nice.png
│   ├── skt.png
│   └── ... (21개)
├── company/            # 회사 에셋
│   └── targetkorea-logo.png
└── README.md
```

## 🖼️ 로고 사용법

### 플랫폼 로고 URL

```
https://raw.githubusercontent.com/DevJihwan/targetkorea-assets/main/logos/[파일명].png
```

예시:
```
https://raw.githubusercontent.com/DevJihwan/targetkorea-assets/main/logos/skt.png
https://raw.githubusercontent.com/DevJihwan/targetkorea-assets/main/logos/meta.png
```

### 회사 로고 URL

```
https://raw.githubusercontent.com/DevJihwan/targetkorea-assets/main/company/targetkorea-logo.png
```

### HTML에서 사용

```html
<!-- 플랫폼 로고 -->
<img src="https://raw.githubusercontent.com/DevJihwan/targetkorea-assets/main/logos/kb-card.png" alt="KB Card">

<!-- 회사 로고 -->
<img src="https://raw.githubusercontent.com/DevJihwan/targetkorea-assets/main/company/targetkorea-logo.png" alt="TARGETKOREA">
```

## 📊 지원 플랫폼 (21개)

### 통신사 (2개)
- SK Telecom
- KT

### 카드사 (6개)
- KB 국민카드
- 롯데카드
- BC카드
- 삼성카드
- 신한카드
- 하나카드

### 멤버십 (3개)
- L.POINT
- 신세계포인트
- OK캐쉬백

### 온라인 플랫폼 (5개)
- Meta
- Kakao
- Google Ads
- Naver
- Instagram

### 서비스 앱 (4개)
- Remember
- 직방
- 호갱노노
- T-map

### 데이터 (1개)
- NICE평가정보

## 🔄 업데이트

### 새 플랫폼 로고 추가
```
1. logos/ 폴더에 이미지 추가
2. 파일명 규칙 준수 (소문자, 하이픈 사용)
3. Commit message: "feat: Add [플랫폼명] logo"
```

### 회사 로고 업데이트
```
1. company/ 폴더의 기존 파일 교체
2. Commit message: "update: Update company logo"
```

## 📝 파일명 규칙

- 소문자 사용
- 공백은 하이픈(-)으로 대체
- 확장자: .png 또는 .jpeg (권장: .png)

예시:
- `kb-card.png` ✅
- `KB Card.PNG` ❌
- `sk-telecom.png` ✅
- `SK텔레콤.png` ❌

## 🔒 파일 크기 권장사항

- 플랫폼 로고: 최대 500KB
- 회사 로고: 최대 200KB
- 해상도: 1000px 이하

## 💡 사용 팁

### CDN 캐싱
GitHub raw URL은 CDN을 통해 전세계적으로 캐싱되어 빠른 로딩 속도를 제공합니다.

### 버전 관리
파일명을 변경하지 않고 내용만 업데이트하면, URL 변경 없이 로고를 교체할 수 있습니다.

---

**Created by:** TARGETKOREA  
**Repository:** https://github.com/DevJihwan/targetkorea-assets  
**Last Updated:** 2025-12-13
