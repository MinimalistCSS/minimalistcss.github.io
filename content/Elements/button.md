---
title: Button
weight: 30
---

.button class allows you to set quick and default button style.

* [size](#size)
* [width](#width)
* [color](#color)
* [border](#border)
* [disabled](#disabled)
* [loading](#loading)
* [round](#round)
* [icon](#icon)
* [shadow](#shadow)
* [gradient](#gradient)
* [hover](#hover)
* [group](#group)


## Size

<div> <span class="hljs-keyword">.button</span> for default size button field</div>
<div> <span class="hljs-keyword">.button-xs</span> for small size button field</div>
<div> <span class="hljs-keyword">.button-md</span> for medium size button field</div>
<div> <span class="hljs-keyword">.button-lg</span> for large size button field</div>

```html
<button class="button">...</button>
<button class="button-xs">...</button>
<button class="button-md">...</button>
<button class="button-lg">...</button>
```

<div class="p-5 border br-b-8 flex flex-wrap">
    <div class="p-3">
        <button class="button">Submit</button>
    </div>
    <div class="p-3">
        <button class="button-xs">Submit</button>
    </div>
    <div class="p-3">
        <button class="button-md">Submit</button>
    </div>
    <div class="p-3">
        <button class="button-lg">Submit</button>
    </div>
</div>


## Width

<div> Use <span class="hljs-keyword">.full</span> or <span class="hljs-keyword">.half</span> class for 100% or 50% width.</div>

```html
<button class="button full">...</button>
<button class="button half">...</button>
```

<div class="p-5 border br-b-8 flex flex-column">
    <div class="p-3">
        <button class="button full">Submit</button>
    </div>
    <div class="p-3">
        <button class="button half">Submit</button>
    </div>
</div>

## Color

To change the color of button change text color, background color and focus color

Don't forget to change the focused outline color. Use <span class="hljs-keyword">.focus-{color}</span> class to change outline color. If don't want focus outline color than use <span class="hljs-keyword">.focus-none</span> class

```html
<!-- Solid Color -->
<button class="button bg-blue white focus-blue">BLUE</button>
<button class="button bg-indigo white focus-indigo">INDIGO</button>
<button class="button bg-purple white focus-purple">PURPLE</button>
<button class="button bg-pink white focus-pink">PINK</button>
<button class="button bg-red white focus-red">RED</button>
<button class="button bg-orange white focus-orange">ORANGE</button>
<button class="button bg-yellow white focus-yellow">YELLOW</button>
<button class="button bg-pear white focus-pear">PEAR</button>
<button class="button bg-green white focus-green">GREEN</button>
<button class="button bg-mint white focus-mint">MINT</button>
<button class="button bg-teal white focus-teal">TEAL</button>
<button class="button bg-wine white focus-wine">WINE</button>
<button class="button bg-brown white focus-brown">BROWN</button>
<button class="button bg-almond white focus-almond">ALMOND</button>
<button class="button bg-slategray white focus-slategray">SLATEGRAY</button>
<button class="button bg-gray white focus-gray">GRAY</button>
<button class="button bg-black white focus-black">BLACK</button>

<!-- Light Color -->
<button class="button bg-blue-lightest blue focus-blue">BLUE</button>
<button class="button bg-indigo-lightest indigo focus-indigo">INDIGO</button>
<button class="button bg-purple-lightest purple focus-purple">PURPLE</button>
<button class="button bg-pink-lightest pink focus-pink">PINK</button>
<button class="button bg-red-lightest red focus-red">RED</button>
<button class="button bg-orange-lightest orange focus-orange">ORANGE</button>
<button class="button bg-yellow-lightest yellow focus-yellow">YELLOW</button>
<button class="button bg-pear-lightest pear focus-pear">PEAR</button>
<button class="button bg-green-lightest green focus-green">GREEN</button>
<button class="button bg-mint-lightest mint focus-mint">MINT</button>
<button class="button bg-teal-lightest teal focus-teal">TEAL</button>
<button class="button bg-wine-lightest wine focus-wine">WINE</button>
<button class="button bg-brown-lightest brown focus-brown">BROWN</button>
<button class="button bg-almond-lightest almond focus-almond">ALMOND</button>
<button class="button bg-slategray-lightest slategray focus-slategray">SLATEGRAY</button>
<button class="button bg-gray-lightest gray focus-gray">GRAY</button>
<button class="button bg-white black focus-white">WHITE</button>
```

<div class="p-5 border br-b-8 flex flex-wrap mb-5">
    <!-- Solid Color -->
    <div class="p-3">
        <button class="button bg-blue white focus-blue">BLUE</button>
    </div>
    <div class="p-3">
        <button class="button bg-indigo white focus-indigo">INDIGO</button>
    </div>
    <div class="p-3">
        <button class="button bg-purple white focus-purple">PURPLE</button>
    </div>
    <div class="p-3">
        <button class="button bg-pink white focus-pink">PINK</button>
    </div>
    <div class="p-3">
        <button class="button bg-red white focus-red">RED</button>
    </div>
    <div class="p-3">
        <button class="button bg-orange white focus-orange">ORANGE</button>
    </div>
    <div class="p-3">
        <button class="button bg-yellow white focus-yellow">YELLOW</button>
    </div>
    <div class="p-3">
        <button class="button bg-pear white focus-pear">PEAR</button>
    </div>
    <div class="p-3">
        <button class="button bg-green white focus-green">GREEN</button>
    </div>
    <div class="p-3">
        <button class="button bg-mint white focus-mint">MINT</button>
    </div>
    <div class="p-3">
        <button class="button bg-teal white focus-teal">TEAL</button>
    </div>
    <div class="p-3">
        <button class="button bg-wine white focus-wine">WINE</button>
    </div>
    <div class="p-3">
        <button class="button bg-brown white focus-brown">BROWN</button>
    </div>
    <div class="p-3">
        <button class="button bg-almond white focus-almond">ALMOND</button>
    </div>
    <div class="p-3">
        <button class="button bg-slategray white focus-slategray">SLATEGRAY</button>
    </div>
    <div class="p-3">
        <button class="button bg-gray white focus-gray">GRAY</button>
    </div>
    <div class="p-3">
        <button class="button bg-black white focus-black">BLACK</button>
    </div>
</div>
<div class="p-5 border br-b-8 flex flex-wrap">
    <div class="p-3">
        <!-- Light Color -->
        <button class="button bg-blue-lightest blue focus-blue">BLUE</button>
    </div>
    <div class="p-3">
        <button class="button bg-indigo-lightest indigo focus-indigo">INDIGO</button>
    </div>
    <div class="p-3">
        <button class="button bg-purple-lightest purple focus-purple">PURPLE</button>
    </div>
    <div class="p-3">
        <button class="button bg-pink-lightest pink focus-pink">PINK</button>
    </div>
    <div class="p-3">
        <button class="button bg-red-lightest red focus-red">RED</button>
    </div>
    <div class="p-3">
        <button class="button bg-orange-lightest orange focus-orange">ORANGE</button>
    </div>
    <div class="p-3">
        <button class="button bg-yellow-lightest yellow focus-yellow">YELLOW</button>
    </div>
    <div class="p-3">
        <button class="button bg-pear-lightest pear focus-pear">PEAR</button>
    </div>
    <div class="p-3">
        <button class="button bg-green-lightest green focus-green">GREEN</button>
    </div>
    <div class="p-3">
        <button class="button bg-mint-lightest mint focus-mint">MINT</button>
    </div>
    <div class="p-3">
        <button class="button bg-teal-lightest teal focus-teal">TEAL</button>
    </div>
    <div class="p-3">
        <button class="button bg-wine-lightest wine focus-wine">WINE</button>
    </div>
    <div class="p-3">
        <button class="button bg-brown-lightest brown focus-brown">BROWN</button>
    </div>
    <div class="p-3">
        <button class="button bg-almond-lightest almond focus-almond">ALMOND</button>
    </div>
    <div class="p-3">
        <button class="button bg-slategray-lightest slategray focus-slategray">SLATEGRAY</button>
    </div>
    <div class="p-3">
        <button class="button bg-gray-lightest gray focus-gray">GRAY</button>
    </div>
    <div class="p-3">
        <button class="button bg-white black focus-white">WHITE</button>
    </div>
</div>

## Border

To change the border color of button use <span class="hljs-keyword">.border-{color}</span> class

```html
<!-- Border Color -->
<button class="button bg-blue-lightest border-blue blue focus-blue">BLUE</button>
<button class="button bg-indigo-lightest border-indigo indigo focus-indigo">INDIGO</button>
<button class="button bg-purple-lightest border-purple purple focus-purple">PURPLE</button>
<button class="button bg-pink-lightest border-pink pink focus-pink">PINK</button>
<button class="button bg-red-lightest border-red red focus-red">RED</button>
<button class="button bg-orange-lightest border-orange orange focus-orange">ORANGE</button>
<button class="button bg-yellow-lightest border-yellow yellow focus-yellow">YELLOW</button>
<button class="button bg-pear-lightest border-pear pear focus-pear">PEAR</button>
<button class="button bg-green-lightest border-green green focus-green">GREEN</button>
<button class="button bg-mint-lightest border-mint mint focus-mint">MINT</button>
<button class="button bg-teal-lightest border-teal teal focus-teal">TEAL</button>
<button class="button bg-wine-lightest border-wine wine focus-wine">WINE</button>
<button class="button bg-brown-lightest border-brown brown focus-brown">BROWN</button>
<button class="button bg-almond-lightest border-almond almond focus-almond">ALMOND</button>
<button class="button bg-slategray-lightest border-slategray slategray focus-slategray">SLATEGRAY</button>
<button class="button bg-gray-lightest border-gray gray focus-gray">GRAY</button>
<button class="button bg-white border-black black focus-white">WHITE</button>
```

<div class="p-5 border br-b-8 flex flex-wrap">
    <div class="p-3">
        <!-- Border Color -->
        <button class="button bg-blue-lightest border-blue blue focus-blue">BLUE</button>
    </div>
    <div class="p-3">
        <button class="button bg-indigo-lightest border-indigo indigo focus-indigo">INDIGO</button>
    </div>
    <div class="p-3">
        <button class="button bg-purple-lightest border-purple purple focus-purple">PURPLE</button>
    </div>
    <div class="p-3">
        <button class="button bg-pink-lightest border-pink pink focus-pink">PINK</button>
    </div>
    <div class="p-3">
        <button class="button bg-red-lightest border-red red focus-red">RED</button>
    </div>
    <div class="p-3">
        <button class="button bg-orange-lightest border-orange orange focus-orange">ORANGE</button>
    </div>
    <div class="p-3">
        <button class="button bg-yellow-lightest border-yellow yellow focus-yellow">YELLOW</button>
    </div>
    <div class="p-3">
        <button class="button bg-pear-lightest border-pear pear focus-pear">PEAR</button>
    </div>
    <div class="p-3">
        <button class="button bg-green-lightest border-green green focus-green">GREEN</button>
    </div>
    <div class="p-3">
        <button class="button bg-mint-lightest border-mint mint focus-mint">MINT</button>
    </div>
    <div class="p-3">
        <button class="button bg-teal-lightest border-teal teal focus-teal">TEAL</button>
    </div>
    <div class="p-3">
        <button class="button bg-wine-lightest border-wine wine focus-wine">WINE</button>
    </div>
    <div class="p-3">
        <button class="button bg-brown-lightest border-brown brown focus-brown">BROWN</button>
    </div>
    <div class="p-3">
        <button class="button bg-almond-lightest border-almond almond focus-almond">ALMOND</button>
    </div>
    <div class="p-3">
        <button class="button bg-slategray-lightest border-slategray slategray focus-slategray">SLATEGRAY</button>
    </div>
    <div class="p-3">
        <button class="button bg-gray-lightest border-gray gray focus-gray">GRAY</button>
    </div>
    <div class="p-3">
        <button class="button bg-white border-black black focus-white">WHITE</button>
    </div>
</div>

## Disabled

<div> Just add disabled attribute to make button disable.</div>

```
<button class="button" disabled>...</button>
```
<div class="p-5 border br-b-8 flex flex-column">
    <div class="p-3">
        <button class="button" disabled>Dont Click Me</button>
    </div>
</div>

## Loading

Use <span class="hljs-keyword">.loading</span> class to set button in loading state. Loading icons inherits the color and size of button.

```html
<button class="button loading">DEFAULT</button>
<button class="button-xs bg-blue white loading">BLUE</button>
<button class="button bg-blue white loading">BLUE</button>
<button class="button-md bg-blue white loading">BLUE</button>
<button class="button-lg bg-gray-lighter gray loading">Gray</button>
```

<div class="p-5 border br-b-8 flex flex-wrap">
    <div class="p-3">
        <button class="button loading">DEFAULT</button>
    </div>
    <div class="p-3">
        <button class="button-xs bg-blue white loading">BLUE</button>
    </div>
    <div class="p-3">
        <button class="button bg-blue white loading">BLUE</button>
    </div>
    <div class="p-3">
        <button class="button-md bg-blue white loading">BLUE</button>
    </div>
    <div class="p-3">
        <button class="button-lg bg-gray-lighter gray loading">Gray</button>
    </div>
</div>

## Round

<div> To make border round use border radius <span class="hljs-keyword">.br-round</span>.</div>

```html
<button class="button br-round">...</button>
<button class="button br-0">...</button>
<button class="button br-6">...</button>
```

<div class="p-5 border br-b-8 flex flex-wrap">
    <div class="p-3">
        <button class="button br-round">Submit</button>
    </div>
    <div class="p-3">
        <button class="button br-0">Submit</button>
    </div>
    <div class="p-3">
        <button class="button br-6">Submit</button>
    </div>
</div>

## Icon

```html
<button class="button">
    <ion-icon name="cart" size="small" class="mr-3"></ion-icon>
    <span>Checkout</span>
</button>

<button class="button bg-pink">
    <span class="input-icon">
        <i data-feather="heart" class="w-5 h-5"></i>
    </span>
</button>

<button class="button">
    SEARCH
    <ion-icon name="search" size="small" class="ml-3"></ion-icon>
</button>
```

<div class="p-5 border br-b-8 flex flex-wrap">
    <div class="p-3">
        <button class="button">
            <ion-icon name="cart" size="small" class="mr-3"></ion-icon>
            <span>Checkout</span>
        </button>
    </div>
    <div class="p-3">
        <button class="button bg-pink">
            <span class="input-icon">
                <i data-feather="heart" class="w-5 h-5"></i>
            </span>
        </button>
    </div>
    <div class="p-3">
        <button class="button">
            SEARCH
            <ion-icon name="search" size="small" class="ml-3"></ion-icon>
        </button>
    </div>
</div>

## Shadow
To add shadow use shadow like <span class="hljs-keyword">.shadow</span> or <span class="hljs-keyword">.shadow-1</span>

```html
<button class="button shadow">Submit</button>
```

<div class="p-5 border br-b-8 flex flex-wrap">
    <div class="p-3">
        <!-- Shadow Color -->
        <button class="button bg-blue-lightest shadow-blue blue focus-blue">BLUE</button>
    </div>
    <div class="p-3">
        <button class="button bg-indigo-lightest shadow-indigo indigo focus-indigo">INDIGO</button>
    </div>
    <div class="p-3">
        <button class="button bg-purple-lightest shadow-purple purple focus-purple">PURPLE</button>
    </div>
    <div class="p-3">
        <button class="button bg-pink-lightest shadow-pink pink focus-pink">PINK</button>
    </div>
    <div class="p-3">
        <button class="button bg-red-lightest shadow-red red focus-red">RED</button>
    </div>
    <div class="p-3">
        <button class="button bg-orange-lightest shadow-orange orange focus-orange">ORANGE</button>
    </div>
    <div class="p-3">
        <button class="button bg-yellow-lightest shadow-yellow yellow focus-yellow">YELLOW</button>
    </div>
    <div class="p-3">
        <button class="button bg-pear-lightest shadow-pear pear focus-pear">PEAR</button>
    </div>
    <div class="p-3">
        <button class="button bg-green-lightest shadow-green green focus-green">GREEN</button>
    </div>
    <div class="p-3">
        <button class="button bg-mint-lightest shadow-mint mint focus-mint">MINT</button>
    </div>
    <div class="p-3">
        <button class="button bg-teal-lightest shadow-teal teal focus-teal">TEAL</button>
    </div>
    <div class="p-3">
        <button class="button bg-wine-lightest shadow-wine wine focus-wine">WINE</button>
    </div>
    <div class="p-3">
        <button class="button bg-brown-lightest shadow-brown brown focus-brown">BROWN</button>
    </div>
    <div class="p-3">
        <button class="button bg-almond-lightest shadow-almond almond focus-almond">ALMOND</button>
    </div>
    <div class="p-3">
        <button class="button bg-slategray-lightest shadow-slategray slategray focus-slategray">SLATEGRAY</button>
    </div>
    <div class="p-3">
        <button class="button bg-gray-lightest shadow-gray gray focus-gray">GRAY</button>
    </div>
    <div class="p-3">
        <button class="button bg-white shadow-black black focus-black">BLACK</button>
    </div>
</div>

## Gradient

Use <span class="hljs-keyword">.{start-color}-{end-color}</span> to add two color liner gradient. <a href="/#">See gradient background color doc</a>

```html
<button class="button orange-red white shadow-2-orange bw-0 focus-red">ORANGE RED</button>
<button class="button linear-blue white shadow-2-blue bw-0 focus-blue">LINEAR BLUE</button>
<button class="button linear-red white shadow-2-red bw-0 focus-red">LINEAR RED</button>
```

<div class="p-5 border br-b-8 flex flex-wrap">
    <div class="p-3">
        <button class="button orange-red white shadow-2-orange bw-0 focus-red">ORANGE RED</button>
    </div>
    <div class="p-3">
        <button class="button linear-blue white shadow-2-blue bw-0 focus-blue">LINEAR BLUE</button>
    </div>
    <div class="p-3">
        <button class="button linear-red white shadow-2-red bw-0 focus-red">LINEAR RED</button>
    </div>
</div>

## Hover

Default hover effect changes the opacity of button but you can change hover effect

```html
<button class="button hover-shift-t-2 ease-200">up on hover</button>
<button class="button hover-rotate-2 ease-200">rotate on hover</button>
<button class="button hover-scale-up-1 ease-200">zoom on hover</button>
<button class="button hover-bg-green ease-200">color on hover</button>
<button class="button hover-bg-gray-darkest ease-200">dark on hover</button>
```

<div class="p-5 border br-b-8 flex flex-wrap">
    <div class="p-3">
        <button class="button hover-shift-t-2 ease-200">up on hover</button>
    </div>
    <div class="p-3">
        <button class="button hover-rotate-2 ease-200">rotate on hover</button>
    </div>
    <div class="p-3">
        <button class="button hover-scale-up-1 ease-200">zoom on hover</button>
    </div>
    <div class="p-3">
        <button class="button hover-bg-green ease-200">color on hover</button>
    </div>
    <div class="p-3">
        <button class="button hover-bg-gray-darkest ease-200">dark on hover</button>
    </div>
</div>

## Group

Use <span class="hljs-keyword">.horizontal-group</span> class to make a horizontal button group or <span class="hljs-keyword">.vertical-group</span> to make a vertical button group

```html
<!-- Horizontal button group -->
<div class="horizontal-group">
    <button type="button" class="button bg-white gray border-gray">Left</button>
    <button type="button" class="button bg-white gray border-gray">Center</button>
    <button type="button" class="button bg-white gray border-gray">Right</button>
</div>

<!-- Vertical button group -->
<div class="vertical-group">
    <button type="button" class="button bg-white gray border-gray">Top</button>
    <button type="button" class="button bg-white gray border-gray">Middle</button>
    <button type="button" class="button bg-white gray border-gray">Bottom</button>
</div>
```

<div class="p-5 border br-b-8 flex flex-column">
    <div class="p-3">
        <!-- Horizontal button group -->
        <div class="horizontal-group">
            <button type="button" class="button bg-white gray border-gray">Left</button>
            <button type="button" class="button bg-white gray border-gray">Center</button>
            <button type="button" class="button bg-white gray border-gray">Right</button>
        </div>
    </div>
    <div class="p-3">
        <!-- Vertical button group -->
        <div class="vertical-group">
            <button type="button" class="button bg-white gray border-gray">Top</button>
            <button type="button" class="button bg-white gray border-gray">Middle</button>
            <button type="button" class="button bg-white gray border-gray">Bottom</button>
        </div>
    </div>
</div>