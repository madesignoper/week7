# 🚀 Week 7 문제

## 🤔 문제 설명

지난 시간 만든 music 서비스를 responsive하게 만들어 봅시다(media query 활용)

<br>

## 💻 예제 화면

1. [메인 페이지 - `index.html`](http://output.jsbin.com/wubudog/)
2. [참고 페이지](https://usecode.pw/understanding-flexbox-everything-you-need-to-know/)

<br>

## 📌 요구사항

### 0. 공통

- 한글이 깨지지 않도록 해야 합니다.

```sh
<meta charset="UTF-8">
```

- css 파일을 만든 뒤, html과 연결 합니다.

- 예제 화면과 동일한 결과물이 출력되는 html 파일과 css파일을 작성해야 합니다.
- html 기본 페이지 구조에 맞게 작성해야 합니다.
  > html, head, body 태그 사용
- 웹 페이지의 title이 표시되어야 합니다.
- 모든 내용은 태그로 작성되어야 합니다.
  > `<p>안녕하세요</p>` (O) / `안녕하세요` (X)

### 1. 메인 페이지

- semantic한 tag를 사용하여 작성해봅시다.
- 예제 화면의 디자인으로 진행하지 않고 변경하셔도 좋습니다.
- 원하는 앨범의 이미지를 활용하셔서 페이지를 구성하셔도 좋습니다.

- 500px을 기준 삼아 크기가 다른 화면에서 좀 더 효과적인 layout을 구성해 봅니다.

### font awesome 관련

font awesome을 사용하기 위해서는 html 파일의 `<head>` 부분에 
  
```html
  <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.css"
    />
  ```
 를 추가해야 합니다.
 
 * footer 부분에 필요한 icon은
 ```html
<i class="fa fa-forward"></i>
<i class="fa fa-pause"></i>
<i class="fa fa-backward"></i>
<i class="fa fa-random"></i>
 ```
 를 사용합니다. (더 추가하셔도 되요!)
<br>

