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
Q. 제작한 폰트를 상업적 용도로 사용할 수 있나요?

- 온글잎에서 제작한 폰트의 사용 범위는 영리적, 상업적 사용을 포함하여 모든 용도에 아무 제한 없이 사용할 수 있어요. 그리고 폰트 파일을 설치할 수 있는 모든 기기와 운영체제에서 사용할 수 있습니다. 당연히 웹폰트, 임베딩도 가능합니다.
- 어디에 쓸 수 있는지 걱정하지 말고 많이 사용해 주세요!


Q. 제작한 폰트를 공유하거나 배포해도 되나요?

- 온글잎에서 제작한 폰트는 자유롭게 공유하거나 배포할 수 있어요.
- 폰트 파일로 공유/배포해도 되지만 ‘온글잎의 공유하기 기능’을 이용해서 공유하는 것을 권장합니다. ‘온글잎의 공유하기 기능’을 이용하면 공유받는 사람이 폰트를 미리 써보고 다운받을 수 있거든요.


Q. 제작한 폰트를 유상으로 판매해도 되나요?

- 온글잎 라이트/베이직/스탠다드 상품으로 제작된 폰트는 온글잎의 동의 없이 유상으로 판매할 수 없어요.
- 온글잎 플러스 상품으로 제작한 폰트만 유상 판매가 가능합니다.


Q. 제작한 폰트의 저작재산권을 제3자에게 양도할 수 있나요?

- 온글잎 라이트/베이직/스탠다드 상품으로 제작된 폰트는 온글잎의 동의 없이 제3자에게 양도, 증여, 담보 제공 등을 할 수 없어요.
- 온글잎 플러스 상품으로 제작한 폰트만 저작재산권을 제3자에게 양도할 수 있습니다.


Q. 제작한 폰트를 온글잎 사이트에서 필수로 배포해야 하나요?

- 온글잎은 다양한 사람들이 각자의 개성이 담긴 폰트를 만들고 공유하며, 폰트로 소통하는 세상을 만들고 싶은 꿈을 가지고 있어요. 그래서 온글잎 라이트/베이직/스탠다드 상품은 폰트를 저렴하게 제작하는 대신, 제작이 완료된 폰트는 필수적으로 온글잎 사이트에서 배포하는 조건에 동의를 받고 있어요.
- 온글잎 플러스 상품으로 제작한 폰트는 온글잎 사이트 배포 여부를 선택할 수 있습니다.


Q. 온글잎에서 다운받은 폰트는 어떤 용도로 사용할 수 있나요?

- 온글잎에서 제작해서 배포하는 모든 폰트는 영리적, 상업적 사용을 포함하여 모든 용도에 아무 제한 없이 사용할 수 있어요. 그리고 폰트 파일을 설치할 수 있는 모든 기기와 운영체제에서 사용할 수 있습니다. 당연히 웹폰트, 임베딩도 가능합니다.


Q. 온글잎 폰트를 사용할 때 출처를 표기해야 하나요?

- 온글잎 폰트를 사용할 때는 출처를 표기하지 않아도 괜찮아요.
- 다만, 혹시 발생할지 모를 문제에 대비해서 출처를 표기하는 것을 권장합니다.
```
