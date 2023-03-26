# Links-Havolalar

## HTML-da giper murojaat (link, ssilka)

Giper murojaatlar HTML sahifalaridan boshqa sahifalarga yoki shu sahifadagi bazi bir hodisalarni amalga oshirish uchun ishlatiladi.

```html
<a href="url" target="_blank">Giper murojaat matni</a>
```

`href` asosiy attribut bo'lib gipermurojaat manzilini belgilab beradi.

`target` belgilangan giper murojaatni qay holatda ochilishini belgilab beradi:

- `_blank` ulangan sahifa yoki dokumentni yangi oynada ochadi
- `_self` ulangan sahifani shu oynaning o'zida ochadi (default qiymat)
- `_parent` ulangan sahifa yangi sahifada ochiladi
- `_top` ulangan sahifani oynaning bor o'lchamida ochadi


# Images_Rasmlar

## HTML-da rasmlar qo'yish

HTML-da rasmlar quyidagi teg bilan qo'yiladi:

```html
<img src="img.png" alt="HTML logo" />
```


<img src="../accets/developer.jpg" width="100%" alt="img attribute">

# Lists

## HTML-da ro'yxatlar

HTML-da ro'yxatlar `<ul>` yoki `<ol>` teglari orqali yaratiladi va har bir ro'yxat elementi `<li>` tegining ichiga yozladi. `<ul>` tartibga solinmagan, `<ol>` tartibga solingan ro'yxat.

```html
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>

<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
```
Natijasi: 
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>

<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>

Ichma-ich listlarni hosil qilish quyidagicha amalga oshiriladi.

```html
<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
  <ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
</ol>
```
<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
  <ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
</ol>

***

### Type va Start attributlari

```html
<ul>
	<li>Item1</li>
	<li>Item2</li>
</ul>

<ol>
	<li>Item1</li>
	<li>Item2</li>
</ol>
<!---Type va start---->
<ul type="disc">
	<li>Item1</li>
	<li>Item2</li>
</ul>

<ol type="I">
	<li>Item1</li>
	<li>Item2</li>
</ol>

<ul type="circle">
	<li>Item1</li>
	<li>Item2</li>
</ul>

<ol type="A">
	<li>Item1</li>
	<li>Item2</li>
</ol>

<ul type="square">
	<li>Item1</li>
	<li>Item2</li>
</ul>

<ol start="20">
	<li>Item1</li>
	<li>Item2</li>
</ol>
```
## Namunalar:

```html
<ul type="disc">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>

<ol type="A">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
```

Natijasi:
<ul type="disc">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>

<ol type="A">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>

***
```html
<ul type="square">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>

<ol start="12">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
```

Natijasi:
<ul type="square">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>

<ol start="12">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>


# Tables

## HTML-da jadvallar

HTML-da jadval `<table>` tegi orqali yaratiladi


```html
<table border="1" width="500">
  <thead>
    <tr>
      <th>Num</th>
      <th>Name</th>
      <th>Surname</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1.</td>
      <td>Mirsoli</td>
      <td>Mirsultonov</td>
    </tr>
    <tr>
      <td>2.</td>
      <td>John</td>
      <td>Doe</td>
    </tr>
    <tr>
      <td>2.</td>
      <td>Bruce</td>
      <td>Lee</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <th colspan="3">Sum: 3</th>
    </tr>
  </tfoot>
</table>
```

Natijasi:
<table border="1" width="500">
  <thead>
    <tr>
      <th>Num</th>
      <th>Name</th>
      <th>Surname</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1.</td>
      <td>Mirsoli</td>
      <td>Mirsultonov</td>
    </tr>
    <tr>
      <td>2.</td>
      <td>John</td>
      <td>Doe</td>
    </tr>
    <tr>
      <td>2.</td>
      <td>Bruce</td>
      <td>Lee</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <th colspan="3">Sum: 3</th>
    </tr>
  </tfoot>
</table>

Jadval tegi va tegishli teglarning attributlari

- `border` - jadvalni o'rab turuvchi chegara chiziqlarni ifodalaydi
- `padding` - jadval katakchasiga qo'shimcha qo'shadi
- `text-align` - jadvaldagi matnlarni tekislash
- `colspan` - jadvaldagi katakchalarni ustun bo'yicha qo'shish
- `rowspan` - jadvaldagi katakchalarni qator bo'yicha qo'shish
