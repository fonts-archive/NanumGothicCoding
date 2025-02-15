# 나눔 고딕 코딩

[배포처 바로가기](https://github.com/naver/nanumfont?tab=readme-ov-file)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `NanumGothicCoding`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/NanumGothicCoding/NanumGothicCoding.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/NanumGothicCoding/NanumGothicCoding.css');
```

### CSS `@font-face`

```css
@font-face {
  font-family: 'NanumGothicCoding';
  font-weight: 400;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/NanumGothicCoding/NanumGothicCoding.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/NanumGothicCoding/NanumGothicCoding.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/NanumGothicCoding/NanumGothicCoding.ttf') format('truetype');
}
@font-face {
  font-family: 'NanumGothicCoding';
  font-weight: 700;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/NanumGothicCoding/NanumGothicCoding-Bold.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/NanumGothicCoding/NanumGothicCoding-Bold.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/NanumGothicCoding/NanumGothicCoding-Bold.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/NanumGothicCoding/subsets/NanumGothicCoding-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url("https://cdn.jsdelivr.net/gh/fonts-archive/NanumGothicCoding/subsets/NanumGothicCoding-dynamic-subset.css");
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.

```css
font-family: "NanumGothicCoding", -apple-system, BlinkMacSystemFont, "Segoe UI",Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
누구나 사용할 수 있고 또 OFL 라이센스 하에서 누구나 재배포하실 수 있습니다.

OFL(Open Font License)이라는 국제적으로 인정받는 공개 글꼴을 위한 라이센스를 채택하여 사용에 대한 제약을 없앰과 동시에 재배포에 대한 제약도 획기적으로 완화하여, 이 라이센스를 명시하기만 하면 다른 프로그램(상용 프로그램 포함)에 이 개발자용 나눔고딕코딩체를 포함하여 재배포하는 것도 허용합니다.

자세한 사항은 아래 OpenFontLicense(https://github.com/naver/nanumfont/wiki/Open-Font-License)를 참고하세요~
```
