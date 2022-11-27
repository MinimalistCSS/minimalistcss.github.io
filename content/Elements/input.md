---
title: Input
weight: 5
---

<span class="hljs-keyword">.input</span> class allows you to set quick and default input style.

* [size](#size)
* [width](#width)
* [disabled](#disabled)
* [round](#round)
* [icon](#icon)
* [shadow](#shadow)
* [color](#color)

## Size

<div> <span class="hljs-keyword">.input</span> for default size input field</div>
<div> <span class="hljs-keyword">.input-xs</span> for small size input field</div>
<div> <span class="hljs-keyword">.input-md</span> for medium size input field</div>
<div> <span class="hljs-keyword">.input-lg</span> for large size input field</div>

```html
<input type="text" class="input" placeholder="First Name">
<input type="text" class="input-xs" placeholder="First Name">
<input type="text" class="input-md" placeholder="First Name">
<input type="text" class="input-lg" placeholder="First Name">
```
<div class="p-5 border br-b-8 flex flex-column">
    <div class="p-3">
        <input type="text" class="input" placeholder="First Name">
    </div>
    <div class="p-3">
        <input type="text" class="input-xs" placeholder="First Name">
    </div>
    <div class="p-3">
        <input type="text" class="input-md" placeholder="First Name">
    </div>
    <div class="p-3">
        <input type="text" class="input-lg" placeholder="First Name">
    </div>
</div>

## Width

<div> Use <span class="hljs-keyword">.full</span> or <span class="hljs-keyword">.half</span> class for 100% or 50% width.</div>

```html
<input type="text" class="input full" placeholder="First Name">
<input type="text" class="input half" placeholder="First Name">
```
<div class="p-5 border br-b-8 flex flex-column">
    <div class="p-3">
        <input type="text" class="input full" placeholder="First Name">
    </div>
    <div class="p-3">
        <input type="text" class="input half" placeholder="First Name">
    </div>
</div>

## Disabled

<div> Just add disabled attribute to make field disable.</div>

```html
<input type="text" class="input" placeholder="First Name" disabled>
```

<div class="p-5 border br-b-8 flex flex-column">
    <div class="p-3">
        <input type="text" class="input" placeholder="First Name" disabled>
    </div>
</div>

## Round

<div> To make border round use border radius <span class="hljs-keyword">.br-round</span>.</div>

```html
<input type="text" class="input br-round" placeholder="First Name">
```

<div class="p-5 border br-b-8 flex flex-column">
    <div class="p-3">
        <input type="text" class="input br-round" placeholder="First Name">
    </div>
</div>

## Icon

```html
<div class="input-wrapper">
    <span class="input-icon"><i data-feather="user" class="w-5 h-5"></i></span>
    <input type="text" class="input bw-0 pl-0" placeholder="First Name">
</div>
```

<div class="p-5 border br-b-8 flex flex-column">
    <div class="p-3">
        <div class="input-wrapper">
            <span class="input-icon"><i data-feather="user" class="w-5 h-5"></i></span>
            <input type="text" class="input bw-0 pl-0" placeholder="First Name">
        </div>
    </div>
</div>

## Shadow
To add shadow use shadow like <span class="hljs-keyword">.shadow</span> or <span class="hljs-keyword">.shadow-1</span>

```html
<input type="text" class="input shadow" placeholder="First Name">
```

<div class="p-5 border br-b-8 flex flex-column">
    <div class="p-3">
        <input type="text" class="input shadow" placeholder="First Name">
    </div>
</div>

## Color
To add the color add classes for border color, text color, placeholder color and focus color.

```html
<input type="text" class="input focus-indigo border-indigo indigo ph-indigo-lighter" placeholder="First Name">
```

<div class="p-5 border br-b-8 flex flex-column">
    <div class="p-3">
        <input type="text" class="input focus-indigo border-indigo indigo ph-indigo-lighter" placeholder="First Name">
    </div>
</div>
