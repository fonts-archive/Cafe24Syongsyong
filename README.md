# 카페24 숑숑

[배포처 바로가기](https://fonts.cafe24.com/)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Cafe24 Syongsyong`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/Cafe24Syongsyong/Cafe24Syongsyong.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/Cafe24Syongsyong/Cafe24Syongsyong.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'Cafe24 Syongsyong';
    font-weight: normal;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/Cafe24Syongsyong/Cafe24Syongsyong.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/Cafe24Syongsyong/Cafe24Syongsyong.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/Cafe24Syongsyong/Cafe24Syongsyong.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/Cafe24Syongsyong/Cafe24Syongsyong.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/Cafe24Syongsyong/subsets/Cafe24Syongsyong-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/Cafe24Syongsyong/subsets/Cafe24Syongsyong-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.


```css
font-family: "Cafe24 Syongsyong", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
카페24에서 제작한 모든 글꼴의 지적 재산권은 카페24(주)에 있습니다.
개인 및 기업 사용자를 포함한 모든 사용자에게 무료로 제공되며 상업적인 사용이 가능합니다. 단, 글꼴 자체를 유료로 판매하는 행위를 금지합니다.
웹디자인, 출판, 웹폰트, CI/BI 제작, 영상 제작 및 자막, 소프트웨어의 번들, 특정 프로그램의 임베드 등 사용범위 제한없이 자유롭게 이용할 수 있습니다.
수정, 재배포가 가능하며 수정한 폰트에도 OFL(OpenFont License)을 적용하여야 합니다.
카페24 폰트를 사용한 결과물은 카페24의 프로모션을 위해 활용될 수 있습니다.
```
