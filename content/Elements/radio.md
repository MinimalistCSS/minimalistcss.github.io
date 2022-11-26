---
title: Radio
weight: 25
---

<span class="hljs-keyword">.radio</span> class allows you to set quick and default radio input style.

<span class="hljs-comment hljs-strong">Note:</span> Add the radio label next to radio input

* [type](#type)
* [disabled](#disabled)
* [color](#color)

## Type

<div> <span class="hljs-keyword">.radio</span> radio input with bullet</div>

```html
<div>
    <input type="radio" class="radio" id="choice-1"/> <label for="choice-1"><span class="fs-s2">Radio</span></label>
</div>
```

<div class="p-5 border br-b-8 flex flex-column">
    <div class="p-3">
        <div>
            <input type="radio" class="radio" id="choice-1"/> <label for="choice-1"><span class="fs-s2">Radio</span></label>
        </div>
    </div>
</div>


## Disabled

<div> Just add disabled attribute to make field disable.</div>

```html
<input type="radio" class="radio" id="choice" disabled/>
<label for="choice">
  <span class="fs-s2">Disabled Radio</span>
</label>

<input type="radio" class="radio" id="choice" checked disabled/>
<label for="choice">
  <span class="fs-s2">Checked Disabled Radio</span>
</label>
```

<div class="p-5 border br-b-8 flex flex-column">
    <div class="p-3">
        <input type="radio" class="radio" id="choice" disabled/>
        <label for="choice">
            <span class="fs-s2">Disabled Radio</span>
        </label>
    </div>
    <div class="p-3">
        <input type="radio" class="radio" id="choice" checked disabled/>
        <label for="choice">
            <span class="fs-s2">Checked Disabled Radio</span>
        </label>
    </div>
</div>



## Color
Add color class to label and radio inherit the color of label. And if you want to change the color of radio only than change the color of text

```html
<input type="radio" class="radio" id="color-1"/>
<label for="color-1" class="blue">
  <span class="fs-s2">Radio</span>
</label>

<input type="radio" class="radio" id="color-2"/>
<label for="color-2" class="indigo">
  <span class="fs-s2 gray">Radio</span>
</label>
```

<div class="p-5 border br-b-8 flex flex-column">
    <div class="p-3">
        <input type="radio" class="radio" id="color-1"/>
        <label for="color-1" class="blue">
            <span class="fs-s2">Radio</span>
        </label>
    </div>
    <div class="p-3">
        <input type="radio" class="radio" id="color-2"/>
        <label for="color-2" class="indigo">
            <span class="fs-s2 gray">Radio</span>
        </label>
    </div>
</div>