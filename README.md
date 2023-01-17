
# Paris
>
> Пет-проект с несколькими интересными решениями.

## Header

Прозрачный хедер, наложенный на секцию _hero_ получен за счет позиционирования блока _header_ :

```css
.header {
  position: absolute;
  width: 100%;
  left: 0;
  top: 0;
  padding-top: 30px;
  z-index: 100; /* обязательно! */
}
```

Для секции _hero_ задается:

```css
.section-hero {
 position: relative;
 background-image: url("../img/first-img.jpg");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
 ```
