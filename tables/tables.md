# Tables

## HTML-da jadvallar

HTML-da jadval `<table>` tegi orqali yaratiladi

[Table]

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

Jadval tegi va tegishli teglarning attributlari

- `border` - jadvalni o'rab turuvchi chegara chiziqlarni ifodalaydi
- `padding` - jadval katakchasiga qo'shimcha qo'shadi
- `text-align` - jadvaldagi matnlarni tekislash
- `colspan` - jadvaldagi katakchalarni ustun bo'yicha qo'shish
- `rowspan` - jadvaldagi katakchalarni qator bo'yicha qo'shish
