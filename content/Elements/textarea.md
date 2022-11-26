---
title: Textarea
weight: 10
---

.input class allows you to set quick and default input style.

* [size](#size)
* [disabled](#disabled)
* [round](#round)
* [shadow](#shadow)
* [color](#color)
* [resize](#resize)

## Size

<div> <span class="hljs-keyword">.textarea</span> for default size textarea field</div>
<div> <span class="hljs-keyword">.textarea-xs</span> for small size textarea field</div>
<div> <span class="hljs-keyword">.textarea-md</span> for medium size textarea field</div>
<div> <span class="hljs-keyword">.textarea-lg</span> for large size textarea field</div>

```html
<textarea class="textarea" rows="5" placeholder="Leave your message here..."></textarea>
<textarea class="textarea-xs" rows="5" placeholder="Leave your message here..."></textarea>
<textarea class="textarea-md" rows="5" placeholder="Leave your message here..."></textarea>
<textarea class="textarea-lg" rows="5" placeholder="Leave your message here..."></textarea>
```
<div class="p-5 border br-b-8 flex flex-column">
    <div class="p-3">
        <textarea class="textarea" rows="5" placeholder="Leave your message here..."></textarea>
    </div>
    <div class="p-3">
        <textarea class="textarea-xs" rows="5" placeholder="Leave your message here..."></textarea>
    </div>
    <div class="p-3">
        <textarea class="textarea-md" rows="5" placeholder="Leave your message here..."></textarea>
    </div>
    <div class="p-3">
        <textarea class="textarea-lg" rows="5" placeholder="Leave your message here..."></textarea>
    </div>
</div>

## Disabled

<div> Just add disabled attribute to make field disable.</div>

```html
<textarea class="textarea" placeholder="Leave your message here..." disabled></textarea>
```

<div class="p-5 border br-b-8 flex flex-column">
    <div class="p-3">
        <textarea class="textarea" placeholder="Leave your message here..." disabled></textarea>
    </div>
</div>

## Round

<div> To make border round use border radius <span class="hljs-keyword">.br-round</span> or <span class="hljs-keyword">.br-0</span>.</div>

```html
<textarea class="textarea br-round" placeholder="Leave your message here..."></textarea>
<textarea class="textarea br-0" placeholder="Leave your message here..."></textarea>
```

<div class="p-5 border br-b-8 flex flex-column">
    <div class="p-3">
        <textarea class="textarea br-round" placeholder="Leave your message here..."></textarea>
    </div>
    <div class="p-3">
        <textarea class="textarea br-0" placeholder="Leave your message here..."></textarea>
    </div>
</div>


## Shadow
To add shadow use shadow like <span class="hljs-keyword">.shadow</span> or <span class="hljs-keyword">.shadow-1</span>

```html
<textarea class="textarea shadow-1" placeholder="Leave your message here..."></textarea>
```

<div class="p-5 border br-b-8 flex flex-column">
    <div class="p-3">
        <textarea class="textarea shadow-1" placeholder="Leave your message here..."></textarea>
    </div>
</div>

## Color
To add the color add classes for border color, text color, placeholder color and focus color.

```html
<textarea class="textarea focus-indigo border-indigo indigo ph-indigo-lighter"></textarea>
```

<div class="p-5 border br-b-8 flex flex-column">
    <div class="p-3">
        <textarea class="textarea focus-indigo border-indigo indigo ph-indigo-lighter" placeholder="Leave your message here..."></textarea>
    </div>
</div>

## Resize

To control the resize behavior of textarea use resize class:

```html
<textarea class="textarea resize-none" placeholder="Leave your message here..."></textarea>
<textarea class="textarea resize-both" placeholder="Leave your message here..."></textarea>
<textarea class="textarea resize-horizontal" placeholder="Leave your message here..."></textarea>
<textarea class="textarea resize-vertical" placeholder="Leave your message here..."></textarea>
```

<div class="p-5 border br-b-8 flex flex-column">
    <div class="p-3">
        <textarea class="textarea resize-none" placeholder="Leave your message here..."></textarea>
    </div>
    <div class="p-3">
        <textarea class="textarea resize-both" placeholder="Leave your message here..."></textarea>
    </div>
    <div class="p-3">
        <textarea class="textarea resize-horizontal" placeholder="Leave your message here..."></textarea>
    </div>
    <div class="p-3">
        <textarea class="textarea resize-vertical" placeholder="Leave your message here..."></textarea>
    </div>
</div>
