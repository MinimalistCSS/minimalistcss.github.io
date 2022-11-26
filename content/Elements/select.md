---
title: Select
weight: 15
---

Use <span class="hljs-keyword">.select</span> class to set quick and default select style.

* [size](#size)
* [width](#width)
* [disabled](#disabled)
* [round](#round)
* [shadow](#shadow)
* [color](#color)

## size

<div> <span class="hljs-keyword">.select</span> for default size select field</div>
<div> <span class="hljs-keyword">.select-xs</span> for small size select field</div>
<div> <span class="hljs-keyword">.select-md</span> for medium size select field</div>
<div> <span class="hljs-keyword">.select-lg</span> for large size select field</div>

```html
<select class="select">...</select>
<select class="select-xs">...</select>
<select class="select-md">...</select>
<select class="select-lg">...</select>
```

<div class="p-5 border br-b-8 flex flex-column">
    <div class="p-3">
        <select class="select">
            <option>Select</option>
            <option>United Kingdom</option>
            <option>Switzerland</option>
            <option>Ireland</option>
        </select>
    </div>
    <div class="p-3">
        <select class="select-xs">
            <option>Select</option>
            <option>United Kingdom</option>
            <option>Switzerland</option>
            <option>Ireland</option>
        </select>
    </div>
    <div class="p-3">
        <select class="select-md">
            <option>Select</option>
            <option>United Kingdom</option>
            <option>Switzerland</option>
            <option>Ireland</option>
        </select>
    </div>
    <div class="p-3">
        <select class="select-lg">
            <option>Select</option>
            <option>United Kingdom</option>
            <option>Switzerland</option>
            <option>Ireland</option>
        </select>
    </div>
</div>

```html
<select class="select" multiple size="3">...</select>
```

<div class="p-5 border br-b-8 flex flex-column">
    <div class="p-3">
        <select class="select" multiple size="3">
            <option>Select</option>
            <option>United Kingdom</option>
            <option>Switzerland</option>
            <option>Ireland</option>
        </select>
    </div>
</div>

## Width

<div> Use <span class="hljs-keyword">.full</span> or <span class="hljs-keyword">.half</span> class for 100% or 50% width.</div>

```html
<select class="select half" multiple size="3">...</select>
<select class="select full">...</select>
```

<div class="p-5 border br-b-8 flex flex-column">
    <div class="p-3">
        <select class="select half" multiple size="3">
            <option>Select</option>
            <option>United Kingdom</option>
            <option>Switzerland</option>
            <option>Ireland</option>
        </select>
    </div>
    <div class="p-3">
        <select class="select full">
            <option>Select</option>
            <option>United Kingdom</option>
            <option>Switzerland</option>
            <option>Ireland</option>
        </select>
    </div>
</div>

## Disabled

<div> Just add disabled attribute to make field disable.</div>

```
<select class="select" disabled>...</select>
```

<div class="p-5 border br-b-8 flex flex-column">
    <div class="p-3">
        <select class="select" disabled>
            <option>Select</option>
            <option>United Kingdom</option>
            <option>Switzerland</option>
            <option>Ireland</option>
        </select>
    </div>
</div>

```
<select class="select" multiple size="3" disabled>...</select>
```

<div class="p-5 border br-b-8 flex flex-column">
    <div class="p-3">
        <select class="select" multiple size="3" disabled>
            <option>Select</option>
            <option>United Kingdom</option>
            <option>Switzerland</option>
            <option>Ireland</option>
        </select>
    </div>
</div>

## Round

<div> To make border round use border radius <span class="hljs-keyword">.br-round</span>.</div>

```
<select class="select br-round">...</select>
```

<div class="p-5 border br-b-8 flex flex-column">
    <div class="p-3">
        <select class="select br-round">
            <option>Select</option>
            <option>United Kingdom</option>
            <option>Switzerland</option>
            <option>Ireland</option>
        </select>
    </div>
</div>

## Shadow
To add shadow use shadow like <span class="hljs-keyword">.shadow</span> or <span class="hljs-keyword">.shadow-1</span>

```
<select class="select shadow">...</select>
```

<div class="p-5 border br-b-8 flex flex-column">
    <div class="p-3">
        <select class="select shadow">
            <option>Select</option>
            <option>United Kingdom</option>
            <option>Switzerland</option>
            <option>Ireland</option>
        </select>
    </div>
</div>

## Color
To add the color add classes for border color, text color, placeholder color and focus color.

```
<select class="select focus-indigo border-indigo bg-indigo white">...</select>
```

<div class="p-5 border br-b-8 flex flex-column">
    <div class="p-3">
        <select class="select focus-indigo border-indigo bg-indigo white">
            <option>Select</option>
            <option>United Kingdom</option>
            <option>Switzerland</option>
            <option>Ireland</option>
        </select>
    </div>
</div>
