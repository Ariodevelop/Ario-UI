# Attributes

## how works

If you write attributes inside tags, css styles will be affected from one attribute to another tag.
<br>
Attributes that have numbers at the end of their names. And it means the effect size and this number is multiplied by 2 and fallow UX patern.

> max counting number of attributes is 6 equal to 12px
> example :

```HTML
<tag- g6><tag-> <!-- Maximum 12 px -->

```

### gap attribute

```HTML
<tag- g0></tag->
...
<tag- g6></tag->
```

> gap attrib make space betwen grids cells like flex and grid

### style in css

```css
[g6] {
  gap: 12px;
}
```

