% Layering and Masking

You will find on this page a collection of [layering](https://fontawesome.com/how-to-use/on-the-web/styling/layering) and [masking](https://fontawesome.com/how-to-use/on-the-web/styling/masking) snippets.

This snippets required to have Font Awesome 5 SVG & JS framework.

Here is a collection of [stacked icons](https://jsfiddle.net/cherrador/jomgLb2h/) by [cherrador](https://github.com/cherrador). ([issue](https://github.com/FortAwesome/Font-Awesome/issues/1446#issuecomment-190011020))

## Adding a new snippet

- Snippet name
- Minimum Font Awesome version (e.g. 5.0.5 free)
- "by" user name
- Links (issues / demos)
- HTML snippet
- `fa-layers` is combined with `fa-fw` **or** icon has class `fa-fw`
- Horizontal line after each snippet
- Snippets are ordered alphabetical by snippet name

## Snippets

### **Bed in house (free)**
- 5.1.0 free
- by [rent-is](https://github.com/rent-is) and [InsanityMeetsHH](https://github.com/InsanityMeetsHH)
- [issue](https://github.com/FortAwesome/Font-Awesome/issues/13812)
- [demo](https://codepen.io/anon/pen/NEXxdV)

```html
<span class="fa-layers fa-fw">
    <i class="fas fa-square-full" data-fa-mask="fas fa-warehouse" data-fa-transform="down-5"></i>
    <i class="fas fa-bed" data-fa-transform="shrink-6 down-2" ></i>
</span>
```

------------

### **Bed in house (pro)**
- 5.1.0 pro
- by [rent-is](https://github.com/rent-is) and [InsanityMeetsHH](https://github.com/InsanityMeetsHH)
- [issue](https://github.com/FortAwesome/Font-Awesome/issues/13812)

```html
<span class="fa-layers fa-fw">
    <i class="fas fa-square-full" data-fa-mask="fal fa-warehouse" data-fa-transform="down-5"></i>
    <i class="fal fa-bed" data-fa-transform="shrink-6 down-2" ></i>
</span>
```

------------

### **Calender with clock**
- 5.0.0 free
- by [tagliala](https://github.com/tagliala)
- [issue 1](https://github.com/FortAwesome/Font-Awesome/issues/8158), [issue 2](https://github.com/FortAwesome/Font-Awesome/issues/14238)
- [demo](https://codepen.io/anon/pen/WYwyLz)

```html
<span class="fa-layers fa-fw">
    <i class="fas fa-circle" data-fa-transform="shrink-7 down-6 right-6" data-fa-mask="fas fa-calendar-alt"></i>
    <i class="far fa-clock" data-fa-transform="shrink-8 down-6 right-6"></i>
</span>
```

------------

### **Clock with arrow**
- 5.0.0 free
- by [tagliala](https://github.com/tagliala)
- [issue](https://github.com/FortAwesome/Font-Awesome/issues/12389)
- [demo](https://jsfiddle.net/tagliala/vLae8ted/60/)

```html
<span class="fa-layers fa-fw">
    <i class="fas fa-clock" data-fa-transform="left-4"></i>
    <i class="fas fa-long-arrow-alt-up" data-fa-transform="right-9"></i>
</span>

<span class="fa-layers fa-fw">
    <i class="fas fa-clock" data-fa-transform="left-4"></i>
    <i class="fas fa-long-arrow-alt-down" data-fa-transform="right-9"></i>
</span>
```

------------

### **Email with cog**
- 5.0.0 free
- by [tagliala](https://github.com/tagliala)
- [issue](https://github.com/FortAwesome/Font-Awesome/issues/14135)
- [demo](http://jsfiddle.net/tagliala/mfopk9qe/7/)

```html
<span class="fa-layers fa-fw">
    <i class="fas fa-circle" data-fa-mask="fas fa-envelope" data-fa-transform="shrink-4 down-4 right-7"></i>
    <i class="fas fa-cog" data-fa-transform="shrink-7 down-4 right-7"></i>
</span>
```

------------

### **File sharing**
- 5.0.0 free
- by [InsanityMeetsHH](https://github.com/InsanityMeetsHH)
- [demo](https://codepen.io/anon/pen/vQpLZr)

```html
<i class="fas fa-share-alt fa-fw" data-fa-mask="fas fa-file" data-fa-transform="shrink-7 down-2.5"></i>
```

------------

### **File with lightbulb**
- 5.3.0 free
- by [tagliala](https://github.com/tagliala)
- [issue](https://github.com/FortAwesome/Font-Awesome/issues/13672)
- [demo](http://jsfiddle.net/tagliala/9tercwpy/28/)

```html
<span class="fa-layers fa-fw">
    <i class="fas fa-circle" data-fa-mask="fas fa-file" data-fa-transform="shrink-3 down-2.5 left-4.5"></i>
    <i class="fas fa-lightbulb" data-fa-transform="shrink-1 down-5 left-5"></i>
</span>
```

------------

### **Info**
- 5.0.0 free
- by [tagliala](https://github.com/tagliala) and [InsanityMeetsHH](https://github.com/InsanityMeetsHH)
- [issue](https://github.com/FortAwesome/Font-Awesome/issues/3114)
- [demo 1](https://jsfiddle.net/tagliala/qu83xrwp/16/), [demo 2](https://codepen.io/anon/pen/RqxrLY)

```html
<span class="fa-layers fa-fw">
    <i class="fas fa-circle"></i>
    <span class="fa-layers-text fa-inverse" data-fa-transform="shrink-3" style="font-weight:900; font-style: italic">i</span>
</span>

<span class="fa-layers fa-fw">
    <i class="far fa-circle"></i>
    <i class="fas fa-info" data-fa-transform="shrink-6"></i>
</span>

<span class="fa-stack">
    <i class="far fa-circle fa-stack-2x"></i>
    <i class="fas fa-info fa-stack-1x"></i>
</span>
```

------------

### **Insert Above / Below**
- 5.0.0 free
- by [CTiedeman](https://github.com/CTiedeman)
- [issue](https://github.com/FortAwesome/Font-Awesome/issues/13863)
- [demo](https://codepen.io/ctiedeman/pen/zJNmRL)

```html
<span class="fa-layers fa-fw">
    <i class="fas fa-minus" data-fa-transform="shrink-4 up-6 right-4"></i>
    <i class="fas fa-reply" data-fa-transform="shrink-5 up-1 left-6 flip-h"></i>
    <i class="fas fa-minus" data-fa-transform="shrink-4 down-2 right-4" style="color:blue"></i>
    <i class="fas fa-minus" data-fa-transform="shrink-4 down-6 right-4"></i>
</span>

<span class="fa-layers fa-fw">
    <i class="fas fa-minus" data-fa-transform="shrink-4 up-6 right-4"></i>
    <i class="fas fa-reply" data-fa-transform="shrink-5 down-1 left-6 flip-v flip-h"></i>
    <i class="fas fa-minus" data-fa-transform="shrink-4 up-2 right-4" style="color:blue"></i>
    <i class="fas fa-minus" data-fa-transform="shrink-4 down-6 right-4"></i>
</span>

<span class="fa-layers fa-fw">
    <i class="fas fa-minus" data-fa-transform="shrink-4 up-6 left-4"></i>
    <i class="fas fa-reply" data-fa-transform="shrink-5 up-1 right-6"></i>
    <i class="fas fa-minus" data-fa-transform="shrink-4 down-2 left-4" style="color:blue"></i>
    <i class="fas fa-minus" data-fa-transform="shrink-4 down-6 left-4"></i>
</span>

<span class="fa-layers fa-fw">
    <i class="fas fa-minus" data-fa-transform="shrink-4 up-6 left-4"></i>
    <i class="fas fa-reply" data-fa-transform="shrink-5 down-1 right-6 flip-v"></i>
    <i class="fas fa-minus" data-fa-transform="shrink-4 up-2 left-4" style="color:blue"></i>
    <i class="fas fa-minus" data-fa-transform="shrink-4 down-6 left-4"></i>
</span>
```

------------

### **Marker with plus**
- 5.0.0 free
- by [tagliala](https://github.com/tagliala)
- [issue](https://github.com/FortAwesome/Font-Awesome/issues/14135)
- [demo](https://jsfiddle.net/tagliala/mfopk9qe/4/)

```html
<span class="fa-layers fa-fw">
    <i class="fas fa-circle" data-fa-mask="fas fa-map-marker-alt" data-fa-transform="shrink-5 down-4 right-5"></i>
    <i class="fas fa-plus" data-fa-transform="shrink-7 down-4 right-5"></i>
</span>
```

------------

### **Phone on square**
- 5.0.0 free
- by [marcoroth](https://github.com/marcoroth) and [InsanityMeetsHH](https://github.com/InsanityMeetsHH)
- [issue](https://github.com/FortAwesome/Font-Awesome/issues/11823)
- [demo](https://codepen.io/anon/pen/NEXxYK)

```html
<span class="fa-layers fa-fw">
    <i class="fas fa-square"></i>
    <i class="fas fa-mobile-alt fa-inverse" data-fa-transform="shrink-6"></i>
</span>

<i class="fas fa-mobile-alt fa-fw" data-fa-mask="fas fa-square" data-fa-transform="shrink-6"></i>
```

------------

### **Program Start / Stop**
- 5.0.0 free
- by [InsanityMeetsHH](https://github.com/InsanityMeetsHH)
- [issue](https://github.com/FortAwesome/Font-Awesome/issues/13766)
- [demo](https://codepen.io/anon/pen/vQdgEE)

```html
<span class="fa-layers fa-fw">
    <i class="fas fa-minus" data-fa-transform="rotate-45 shrink-5 left-3 down-3"></i>
    <i class="fas fa-minus" data-fa-transform="rotate-135 shrink-5 right-3 down-3"></i>
    <i class="fas fa-minus" data-fa-transform="rotate-45 shrink-5 right-3 up-3"></i>
    <i class="fas fa-minus" data-fa-transform="rotate-135 shrink-5 left-3 up-3"></i>
    <i class="fas fa-minus" data-fa-transform="rotate-90 shrink-8"></i>
</span>

<span class="fa-layers fa-fw">
    <i class="far fa-circle" data-fa-transform=""></i>
    <i class="fas fa-minus" data-fa-transform="rotate-60 shrink-5 left-2 down-1.65"></i>
    <i class="fas fa-minus" data-fa-transform="rotate-120 shrink-5 right-2 down-1.65"></i>
    <i class="fas fa-minus" data-fa-transform="rotate-180 shrink-4 up-2.65"></i>
</span>
```

------------

### **Save icon set**
- 5.0.13 free
- by [InsanityMeetsHH](https://github.com/InsanityMeetsHH)
- [issue](https://github.com/FortAwesome/Font-Awesome/issues/14152)
- [demo](https://codepen.io/anon/pen/ePjMBo)

```html
<i class="fas fa-save fa-fw"></i>

<span class="fa-layers fa-fw">
    <i class="fas fa-circle" data-fa-transform="shrink-10 down-5 right-5" data-fa-mask="fas fa-save"></i>
    <i class="fas fa-times" data-fa-transform="shrink-12 down-5 right-5"></i>
</span>

<span class="fa-layers fa-fw">
    <i class="fas fa-circle" data-fa-transform="shrink-10 down-5 right-5" data-fa-mask="fas fa-save"></i>
    <i class="fas fa-check" data-fa-transform="shrink-12 down-5 right-5"></i>
</span>

<span class="fa-layers fa-fw">
    <i class="fas fa-circle" data-fa-transform="shrink-10 down-5 right-5" data-fa-mask="fas fa-save"></i>
    <i class="fas fa-arrow-down" data-fa-transform="shrink-12 down-5 right-5"></i>
</span>

<span class="fa-layers fa-fw">
    <i class="fas fa-circle" data-fa-transform="shrink-10 down-5 right-5" data-fa-mask="fas fa-save"></i>
    <i class="fas fa-arrow-up" data-fa-transform="shrink-12 down-5 right-5"></i>
</span>
```

------------

### **Search with plus**
- 5.0.0 free
- by [tagliala](https://github.com/tagliala)
- [issue](https://github.com/FortAwesome/Font-Awesome/issues/12445)
- [demo](https://jsfiddle.net/vLae8ted/79/)

```html
<span class="fa-layers fa-fw">
    <i class="fas fa-search"></i>
    <i class="fas fa-plus" data-fa-transform="shrink-6 down-2 right-10"></i>
</span>
```

------------

### **Space shuttle launch**
- 5.0.0 free
- by [InsanityMeetsHH](https://github.com/InsanityMeetsHH)
- [demo](https://codepen.io/anon/pen/XyVXqM)

```html
<span class="fa-layers fa-fw">
    <i class="fab fa-gripfire" data-fa-transform="down-4 shrink-8 rotate-180" style="color: tomato;"></i>
    <i class="fas fa-space-shuttle" data-fa-transform="up-3 shrink-8 rotate-270" ></i>
</span>
```

------------

### **Unisex**
- 5.0.5 free
- by [tagliala](https://github.com/tagliala)
- [issue](https://github.com/FortAwesome/Font-Awesome/issues/14281)
- [demo](https://jsfiddle.net/tagliala/wks0e6pa/7/)

```html
<span class="fa-layers fa-fw">
    <i class="fas fa-square-full" data-fa-transform="shrink-4.5 down-2.25 right-5.35" data-fa-mask="fas fa-male"></i>
    <i class="fas fa-square-full" data-fa-transform="shrink-4.5 down-2.25 left-5.35" data-fa-mask="fas fa-female"></i>
</span>
```

------------

### **User with pencil**
- 5.0.11 free
- by [tagliala](https://github.com/tagliala)
- [issue](https://github.com/FortAwesome/Font-Awesome/issues/1181#issuecomment-350016641)
- [demo](https://jsfiddle.net/tagliala/8oqL3b5p/)

```html
<span class="fa-layers fa-fw">
    <i class="fas fa-pencil-alt" data-fa-transform="shrink-8 down-6 right-6" data-fa-mask="fas fa-user"></i>
    <i class="fas fa-pencil-alt" data-fa-transform="shrink-9 down-6 right-6"></i>
</span>
```

------------

### **Voicemail**
- 5.0.9 free
- by [GabrielBuenoOliveira](https://github.com/GabrielBuenoOliveira)
- [issue](https://github.com/FortAwesome/Font-Awesome/issues/2637)
- [demo](https://codepen.io/anon/pen/RqxrBq)

```html
<span class="fa-layers fa-fw">
    <i class="fas fa-tape fa-flip-horizontal" data-fa-transform="right-5 shrink-3" ></i>
    <i class="fas fa-tape" data-fa-transform="left-5 shrink-3" ></i>  
</span>
```

------------

### **Window search**
- 5.0.0 free
- by [tagliala](https://github.com/tagliala)
- [issue](https://github.com/FortAwesome/Font-Awesome/issues/13595)
- [demo](https://jsfiddle.net/tagliala/ydq3jrne/51/)

```html
<span class="fa-layers fa-fw">
   <i class="fas fa-circle" data-fa-transform="shrink-6 down-5 right-6" data-fa-mask="far fa-window-maximize"></i>
   <i class="fas fa-search" data-fa-transform="shrink-8 down-5 right-6"></i>
</span>
```

------------
