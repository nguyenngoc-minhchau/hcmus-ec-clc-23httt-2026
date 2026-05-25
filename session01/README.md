# Layout website with CSS

## 1 - CSS - Format Selector name

Define Selector name

```css
style-name {
    css-property: value;
}
```

1. CSS - Element => HTML Tag

``` css
h1 {
    color: red;
}
```

2. CSS - ID => #StyleName

```css
#container {
    background-color: red;
}
```

3. CSS - Class => .StyleName

```css
.product-item {
    background-color: #CC3366;
    color: #FFFFFF;
}
```

4. CSS - Element.Class => h1.product-item

```css
h1.product-item {
    font-size: 2rem;
}
```

5. CSS - Grouping => h1, .product-item, #container

```css
h1, .prodcut-item, #container {
    font-size: italic;
}
```

6. CSS - Contextual => div p

```css
div p {
    color: #66CC33;
}

<div>
    <p>aa</p>
    <ul>
        <li>
            <p>axa</p>
        </li>
    </ul>
</div> 

div > p {
    background-color: #CC3366;
}
```

7. CSS - Pesudo => a:hover

```css
a {
    background-color: #CC3366;
}

a:hover {
    background-color: #33CC66;
}

a:active {
    background-color: #6633CC;
}
```
## 2 - Responsive
```css
@media (min-width: ...) {
    ...
}
```

Screen size: mobile, tablet, desktop (size < fullHD), Large-Screen