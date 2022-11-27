---
title: after/before
weight: 10
---

# ::after and ::before

* [icon](#icon)
* [position](#position)
* [color](#color)
* [size](#size)
* [margin](#margin)
* [shadow](#shadow)
* [examples](#examples)

## Icon

<div class="flex flex-column">
    <div class="p-3">
        <div class="mt-5 table-container cell-border table-head text-center">
            <table>
                <thead>
                    <tr>
                        <td>Example</td>
                        <td>Name</td>
                        <td>Class</td>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td><div class="before-plus"></div></td>
                        <td><div class="">plus</div></td>
                        <td><code>.before-plus</code></td>
                    </tr>
                    <tr>
                        <td><div class="before-minus"></div></td>
                        <td><div class="">minus</div></td>
                        <td><code>.before-minus</code></td>
                    </tr>
                    <tr>
                        <td><div class="before-times"></div></td>
                        <td><div class="">times</div></td>
                        <td><code>.before-times</code></td>
                    </tr>
                    <tr>
                        <td><div class="before-times-large"></div></td>
                        <td><div class="">times-large</div></td>
                        <td><code>.before-times-large</code></td>
                    </tr>
                    <tr>
                        <td><div class="before-circle-plus"></div></td>
                        <td><div class="">circle-plus</div></td>
                        <td><code>.before-circle-plus</code></td>
                    </tr>
                    <tr>
                        <td><div class="before-circle-minus"></div></td>
                        <td><div class="">circle-minus</div></td>
                        <td><code>.before-circle-minus</code></td>
                    </tr>
                    <tr>
                        <td><div class="before-circle-times"></div></td>
                        <td><div class="">circle-times</div></td>
                        <td><code>.before-circle-times</code></td>
                    </tr>
                    <tr>
                        <td><div class="before-hash"></div></td>
                        <td><div class="">hash</div></td>
                        <td><code>.before-hash</code></td>
                    </tr>
                    <tr>
                        <td><div class="before-ellipsis"></div></td>
                        <td><div class="">ellipsis</div></td>
                        <td><code>.before-ellipsis</code></td>
                    </tr>
                    <tr>
                        <td><div class="before-ellipsis-midline"></div></td>
                        <td><div class="">ellipsis-midline</div></td>
                        <td><code>.before-ellipsis-midline</code></td>
                    </tr>
                    <tr>
                        <td><div class="before-ellipsis-vertical"></div></td>
                        <td><div class="">ellipsis-vertical</div></td>
                        <td><code>.before-ellipsis-vertical</code></td>
                    </tr>
                    <tr>
                        <td><div class="before-arrow-left"></div></td>
                        <td><div class="">arrow-left</div></td>
                        <td><code>.before-arrow-left</code></td>
                    </tr>
                    <tr>
                        <td><div class="before-arrow-right"></div></td>
                        <td><div class="">arrow-right</div></td>
                        <td><code>.before-arrow-right</code></td>
                    </tr>
                    <tr>
                        <td><div class="before-arrow-up"></div></td>
                        <td><div class="">arrow-up</div></td>
                        <td><code>.before-arrow-up</code></td>
                    </tr>
                    <tr>
                        <td><div class="before-arrow-down"></div></td>
                        <td><div class="">arrow-down</div></td>
                        <td><code>.before-arrow-down</code></td>
                    </tr>
                    <tr>
                        <td><div class="before-triangle-left"></div></td>
                        <td><div class="">triangle-left</div></td>
                        <td><code>.before-triangle-left</code></td>
                    </tr>
                    <tr>
                        <td><div class="before-triangle-right"></div></td>
                        <td><div class="">triangle-right</div></td>
                        <td><code>.before-triangle-right</code></td>
                    </tr>
                    <tr>
                        <td><div class="before-triangle-up"></div></td>
                        <td><div class="">triangle-up</div></td>
                        <td><code>.before-triangle-up</code></td>
                    </tr>
                    <tr>
                        <td><div class="before-triangle-down"></div></td>
                        <td><div class="">triangle-down</div></td>
                        <td><code>.before-triangle-down</code></td>
                    </tr>
                    <tr>
                        <td><div class="before-asterisk"></div></td>
                        <td><div class="">asterisk</div></td>
                        <td><code>.before-asterisk</code></td>
                    </tr>
                    <tr>
                        <td><div class="before-menu"></div></td>
                        <td><div class="">menu</div></td>
                        <td><code>.before-menu</code></td>
                    </tr>
                    <tr>
                        <td><div class="before-checkmark"></div></td>
                        <td><div class="">checkmark</div></td>
                        <td><code>.before-checkmark</code></td>
                    </tr>
                </tbody>
            </table>
        </div>
    </div>
</div>

## Position

Use class <span class="hljs-keyword">.after-right</span> to float right <span class="hljs-keyword">.after-{icon}</span>.

available: <span class="hljs-keyword">.after-left .after-right .before-left .before-right</span>.

```html
<div class="...after-plus after-right">Open This</div>
<div class="...after-minus after-right">Close This</div>
```

<div class="flex flex-column">
    <div class="p-3">
        <div class="m-1 bg-blue-darkest white br-6 p-4 fs-s1 after-plus after-right">Open This</div>
        <div class="m-1 bg-gray-darkest white br-6 p-4 fs-s1 after-minus after-right">Close This</div>
    </div>
</div>

## Color

Pseudo elements inherits font-color and size.

```html
<div class="...after-plus after-right">Open This</div>
<div class="...after-minus after-right"><span class="red">Close This</span></div>
```

<div class="flex flex-column">
    <div class="p-3">
        <div class="m-1 bg-blue-lighter black br-6 p-4 fs-s1 after-plus after-right">Open This</div>
        <div class="m-1 bg-gray-lighter black br-6 p-4 fs-s1 after-minus after-right"><span class="red">Close This</span></div>
    </div>
</div>

## Size

Pseudo elements inherits font-size. But if you want to increase or decrease size, you can use <a href="/interaction/scale">scale</a> class like <span class="hljs-keyword">.after-scale-up-3</span>.

```html
<div class="...after-plus after-right">...</div>
<div class="...after-plus after-right after-scale-up-3">...</div>
```

<div class="flex flex-column">
    <div class="p-3">
        <div class="m-1 bg-gray-lighter gray-darkest br-6 p-4 fs-s1 after-plus after-right">Default size</div>
        <div class="m-1 bg-gray-lighter gray-darkest br-6 p-4 fs-s1 after-plus after-right after-scale-up-3">With scale-up-3 </div>
    </div>
</div>

## Margin

Margin can be applied on pseudo elements, you can use <a href="/spacing/margin">margin</a> class like <span class="hljs-keyword">.after-mr-5</span>.

```html
<div class="...before-menu">Without margin</div>
<div class="...before-menu before-mx-3">With margin</div>
```

<div class="flex flex-column">
    <div class="p-3">
        <div class="m-1 bg-gray-lighter gray-darkest br-6 p-4 fs-s1 before-menu">Without margin</div>
        <div class="m-1 bg-gray-lighter gray-darkest br-6 p-4 fs-s1 before-menu before-mx-3">With margin</div>
    </div>
</div>

## Examples

```html
<button class="button after-arrow-right after-ml-3">Enter</button>
<h2 class="before-hash before-mr-2 gray-lighter hover-gray-light"><a href="#" class="gray no-underline">pseudo elements</a></h2>
```

<button class="button after-arrow-right after-ml-3">Enter</button>
<h2 class="before-hash before-mr-2 gray-lighter hover-gray-light"><a href="#" class="gray no-underline">pseudo elements</a></h2>

