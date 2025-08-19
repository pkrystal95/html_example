# Typography

> 수정사항을 바로 확인하기 위해서는 Live Server를 이용하자!!!

## 1. 기초

```html
<!-- html 주석 -->
<!DOCTYPE html>
<html>
  <body>
    <h1>My First Heading</h1>

    <p>My first paragraph.</p>
  </body>
</html>
```

## 1. Heading

```html
<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
<h4>This is heading 4</h4>
<h5>This is heading 5</h5>
<h6>This is heading 6</h6>
```

## 2. Paragraph(단락)

```html
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
```

## 3. List(목록)

### 순서 있는 목록

```html
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
```

### 순서 없는 목록

```html
<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
```

## 4. Link

```html
<a href="https://github.com/pkrystal95">This is a link</a>
```

## 5. Image

```html
<img src="이미지 링크" alt="이미지 설명" width="100" height="100" />
<<<<<<< HEAD
```

<br />
<br />

# Form

## 0. 구조

```html
<form>
  <!-- 여기에 폼 구조 작성 -->
</form>
```

> 값을 입력 받아 naver 검색을 진행하는 실습

## 1. 텍스트(input)

```html
<input type="text" />
```

## 2. 드롭다운(select)

```html
<select name="query">
  <option value="JAVA">JAVA</option>
  <option value="SQL">SQL</option>
  <option value="HTML">HTML</option>
</select>
```

## 3. 라디오

```html
<!-- 타입을 라디오로 정의 -->
<input type="radio" />

<label>
  <input type="radio" name="query" value="스프링부트" />
  스프링부트
</label>
```

## 4. 자동완성(datalist)

```html
<label>
  <input type="text" name="query" list="keywords" />
  <datalist id="keywords">
    <option value="HTML"></option>
    <option value="CSS"></option>
    <option value="JavaScript"></option>
  </datalist>
</label>

```
