---
title: In progress
weight: 5
---

Sometimes <span class="hljs-keyword">.spinner</span> is not sufficient to indicate loading state. <span class="hljs-keyword">.in-progress</span> class allows you to set al loading style of content. It can be used to create a content placeholder in loading state or add progress effect to anything like progress bar or button.

## Examples

```html
<div class="in-progress">
    <div class="h-3 bg-gray-light w-50pc"></div>
    <div class="h-3 bg-gray-light my-2"></div>
    <div class="h-3 bg-gray-light my-2"></div>
    <div class="h-3 bg-gray-light my-2"></div>
</div>
```

<div class="in-progress">
    <div class="h-3 bg-gray-light w-50pc"></div>
    <div class="h-3 bg-gray-light my-2"></div>
    <div class="h-3 bg-gray-light my-2"></div>
    <div class="h-3 bg-gray-light my-2"></div>
</div>

```html
<button class="button bg-blue in-progress" disabled>Loading...</button>
```

<button class="button bg-blue in-progress" disabled>Loading...</button>

```html
<div class="bg-gray-lighter br-round">
    <div class="bg-blue w-60pc h-1 br-round in-progress"></div>
</div>
```

<div class="bg-gray-lighter br-round">
    <div class="bg-blue w-60pc h-1 br-round in-progress"></div>
</div>