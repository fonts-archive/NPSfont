# 국민연금체

[배포처 바로가기](https://blog.naver.com/pro_nps/223057676647)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `NPSfont`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/NPSfont/NPSfont.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/NPSfont/NPSfont.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'NPSfont';
    font-weight: 400;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/NPSfont/NPSfont-Regular.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/NPSfont/NPSfont-Regular.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/NPSfont/NPSfont-Regular.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/NPSfont/NPSfont-Regular.ttf') format('truetype');
}
@font-face {
    font-family: 'NPSfont';
    font-weight: 700;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/NPSfont/NPSfont-Bold.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/NPSfont/NPSfont-Bold.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/NPSfont/NPSfont-Bold.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/NPSfont/NPSfont-Bold.ttf') format('truetype');
}
@font-face {
    font-family: 'NPSfont';
    font-weight: 800;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/NPSfont/NPSfont-ExtraBold.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/NPSfont/NPSfont-ExtraBold.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/NPSfont/NPSfont-ExtraBold.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/NPSfont/NPSfont-ExtraBold.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/NPSfont/subsets/NPSfont-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/NPSfont/subsets/NPSfont-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.


```css
font-family: "NPSfont", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
국민연금공단이 새롭게 배포하는 "국민연금체 Bold와 Extra Bold"도 기존의 국민연금체와 같이 개인 및 기업을 포함한 모든 분들에게 무료로 제공되고, 여러분의 필요에 따라 다양한 분야에서 폭넓게 사용하실 수 있습니다.

(주의!! 본 서체의 글꼴 자체를 유료로 판매하거나 왜곡, 변형할 수 없습니다.)
[출처] 더 두꺼워진 국민연금체 Bold와 Extra Bold가 탄생했습니다!! 무료로 다운로드 받아 사용해보세요! :)|작성자 국민연금공단
```
