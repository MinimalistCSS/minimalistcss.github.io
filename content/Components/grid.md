---
title: Grid
weight: 5
---

* [grid](#grid)
* [responsive grid](#responsive-grid)
* [equal width column](#equal-width-column)

## Grid

```html
<div class="flex">
    <div class="w-25pc">...</div>
    <div class="w-25pc">...</div>
    <div class="w-25pc">...</div>
    <div class="w-25pc">...</div>
</div>
```

<div class="p-5 border br-b-8">
    <div class="flex flex-wrap my-2 fs-s2 gray text-center">
        <div class="w-25pc bg-gray-lightest border-gray-light p-3">.w-25pc</div>
        <div class="w-25pc bg-gray-lightest border-gray-light p-3">.w-25pc</div>
        <div class="w-25pc bg-gray-lightest border-gray-light p-3">.w-25pc</div>
        <div class="w-25pc bg-gray-lightest border-gray-light p-3">.w-25pc</div>
    </div>
</div>

## Responsive Grid

```html
<div class="flex flex-wrap">
    <div class="w-100pc md-w-50pc lg-w-25pc">A</div>
    <div class="w-100pc md-w-50pc lg-w-25pc">B</div>
    <div class="w-100pc md-w-50pc lg-w-25pc">C</div>
    <div class="w-100pc md-w-50pc lg-w-25pc">D</div>
</div>
```

<div class="p-5 border br-b-8">
    <div class="flex flex-wrap my-2 fs-s2 gray text-center">
        <div class="w-100pc md-w-50pc lg-w-25pc bg-gray-lightest border-gray-light p-3">A</div>
        <div class="w-100pc md-w-50pc lg-w-25pc bg-gray-lightest border-gray-light p-3">B</div>
        <div class="w-100pc md-w-50pc lg-w-25pc bg-gray-lightest border-gray-light p-3">C</div>
        <div class="w-100pc md-w-50pc lg-w-25pc bg-gray-lightest border-gray-light p-3">D</div>
    </div>
</div>

## Equal width column

All the column will share equal width

```html
<div class="flex">
    <div class="flex-equal">A</div>
    <div class="flex-equal">B</div>
    <div class="flex-equal">C</div>
    <div class="flex-equal">D</div>
</div>

<div class="flex">
    <div class="flex-equal">A</div>
    <div class="flex-equal">B</div>
    <div class="flex-equal">C</div>
    <div class="flex-equal">D</div>
    <div class="flex-equal">E</div>
    <div class="flex-equal">F</div>
</div>
```

<div class="p-5 border br-b-8">
    <div class="flex my-2 fs-s2 gray text-center">
        <div class="flex-equal bg-gray-lightest border-gray-light p-3">A</div>
        <div class="flex-equal bg-gray-lightest border-gray-light p-3">B</div>
        <div class="flex-equal bg-gray-lightest border-gray-light p-3">C</div>
        <div class="flex-equal bg-gray-lightest border-gray-light p-3">D</div>
    </div>
    <div class="flex my-3 fs-s2 gray text-center">
        <div class="flex-equal bg-gray-lightest border-gray-light p-3">A</div>
        <div class="flex-equal bg-gray-lightest border-gray-light p-3">B</div>
        <div class="flex-equal bg-gray-lightest border-gray-light p-3">C</div>
        <div class="flex-equal bg-gray-lightest border-gray-light p-3">D</div>
        <div class="flex-equal bg-gray-lightest border-gray-light p-3">E</div>
        <div class="flex-equal bg-gray-lightest border-gray-light p-3">F</div>
    </div>
</div>

<div class="p-5 mt-5 border br-8 fs-s2 gray text-center">
    <div class="flex my-2">
        <div class="w-33pc bg-gray-lightest border-gray-light p-3">1/3</div>
        <div class="w-33pc bg-gray-lightest border-gray-light p-3">1/3</div>
        <div class="w-33pc bg-gray-lightest border-gray-light p-3">1/3</div>
    </div>
    <div class="flex my-2">
        <div class="w-50pc bg-gray-lightest border-gray-light p-3">1/2</div>
        <div class="w-50pc bg-gray-lightest border-gray-light p-3">1/2</div>
    </div>
    <div class="flex my-2">
        <div class="w-100pc bg-gray-lightest border-gray-light p-3">1/2</div>
    </div>
</div>