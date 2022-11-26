---
title: Checkbox
weight: 20
---

<span class="hljs-keyword">.checkbox</span> class allows you to set quick and default checkbox input style.

<span class="hljs-comment hljs-strong">Note:</span> Add the checkbox label next to checkbox input

* [type](#type)
* [disabled](#disabled)
* [color](#color)

## Type

<div> <span class="hljs-keyword">.checkbox</span> checkbox with checkmark</div>
<div> <span class="hljs-keyword">.checkbox-bullet</span> checkbox with bullet</div>
<div> <span class="hljs-keyword">.checkbox-round</span> round checkbox with checkmark</div>

```html
<div>
    <input type="checkbox" class="checkbox" id="choice-1"/> <label for="choice-1"><span class="fs-s2">Checkbox</span></label>
</div>

<div>
    <input type="checkbox" class="checkbox-bullet" id="choice-2"/> <label for="choice-2"><span class="fs-s2">Bullet Checkbox</span></label>
</div>

<div>
    <input type="checkbox" class="checkbox-round" id="choice-3"/> <label for="choice-3"><span class="fs-s2">Round Checkbox</span></label>
</div>
```

<div class="p-5 border br-b-8 flex flex-column">
    <div class="p-3">
        <div>
            <input type="checkbox" class="checkbox" id="choice-1"/> <label for="choice-1"><span class="fs-s2">Checkbox</span></label>
        </div>
    </div>
    <div class="p-3">
        <div>
            <input type="checkbox" class="checkbox-bullet" id="choice-2"/> <label for="choice-2"><span class="fs-s2">Bullet Checkbox</span></label>
        </div>
    </div>
    <div class="p-3">
        <div>
            <input type="checkbox" class="checkbox-round" id="choice-3"/> <label for="choice-3"><span class="fs-s2">Round Checkbox</span></label>
        </div>
    </div>
</div>

## Disabled

<div> Just add disabled attribute to make field disable.</div>

```html
<input type="checkbox" class="checkbox" id="choice" disabled/>
<label for="choice">
  <span class="fs-s2">Disabled Checkbox</span>
</label>

<input type="checkbox" class="checkbox" id="choice" checked disabled/>
<label for="choice">
  <span class="fs-s2">Checked Disabled Checkbox</span>
</label>
```

<div class="p-5 border br-b-8 flex flex-column">
    <div class="p-3">
        <input type="checkbox" class="checkbox" id="choice" disabled/>
        <label for="choice">
            <span class="fs-s2">Disabled Checkbox</span>
        </label>
    </div>
    <div class="p-3">
        <input type="checkbox" class="checkbox" id="choice" checked disabled/>
        <label for="choice">
            <span class="fs-s2">Checked Disabled Checkbox</span>
        </label>
    </div>
</div>



## Color
Add color class to label and checkbox inherit the color of label. And if you want to change the color of checkbox only than change the color of text

```html
<input type="checkbox" class="checkbox" id="color-1"/>
<label for="color-1" class="blue">
  <span class="fs-s2">Checkbox</span>
</label>

<input type="checkbox" class="checkbox" id="color-2"/>
<label for="color-2" class="indigo">
  <span class="fs-s2 gray">Checkbox</span>
</label>
```

<div class="p-5 border br-b-8 flex flex-column">
    <div class="p-3">
        <input type="checkbox" class="checkbox" id="color-1"/>
        <label for="color-1" class="blue">
            <span class="fs-s2">Checkbox</span>
        </label>
    </div>
    <div class="p-3">
        <input type="checkbox" class="checkbox" id="color-2"/>
        <label for="color-2" class="indigo">
            <span class="fs-s2 gray">Checkbox</span>
        </label>
    </div>
</div>
