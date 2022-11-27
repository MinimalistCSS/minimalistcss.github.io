---
title: Cards
weight: 25
---

## Card with image on top

```html
<div class="w-33pc br-8 shadow-2 m-3">
    <img class="br-t-8 w-100pc h-auto" src="https://images.unsplash.com/photo-1568960901097-6df09601f134?auto=format&amp;fit=crop&amp;w=800&amp;q=60" alt="" srcset="">
    <div class="p-5">
        <h2 class="gray-light fs-m2 fw-600">Card Without Border</h2>
        <p class="my-3 lh-3 gray-lighter opacity-60">Lorem ipsum dolor sit amet, consectetur adipisicing elit.
        Voluptatibus quia, nulla! Maiores et perferendis eaque, exercitationem praesentium nihil.
        </p>
        <button class="inline-block mr-3 mt-5 br-3 bw-0 px-3 py-2 fs-s2 bg-gray-lighter black pointer hover-bg-gray-light">Read
        More</button>
    </div>
</div>

<div class="w-33pc br-8 shadow-1 border-gray m-3">
    <img class="br-t-8 w-100pc h-auto" src="https://images.unsplash.com/photo-1568960901097-6df09601f134?auto=format&amp;fit=crop&amp;w=800&amp;q=60" alt="" srcset="">
    <div class="p-5">
        <h2 class="gray-light fs-m2 fw-600">Card With Border</h2>
        <p class="my-3 lh-3 gray-lighter opacity-60">Lorem ipsum dolor sit amet, consectetur adipisicing elit.
        Voluptatibus quia, nulla! Maiores et perferendis eaque, exercitationem praesentium nihil.
        </p>
        <button class="inline-block mr-3 mt-5 br-3 bw-0 px-3 py-2 fs-s2 bg-gray-lighter black pointer hover-bg-gray-light">Read
        More</button>
    </div>
</div>

<div class="w-33pc br-8 bg-blue border-blue m-3">
    <img class="br-t-8 w-100pc h-auto" src="https://images.unsplash.com/photo-1568960901097-6df09601f134?auto=format&amp;fit=crop&amp;w=800&amp;q=60" alt="" srcset="">
    <div class="p-5">
        <h2 class="gray-light fs-m2 fw-600">Card Without Border</h2>
        <p class="my-3 lh-3 gray-lighter opacity-60">Lorem ipsum dolor sit amet, consectetur adipisicing elit.
        Voluptatibus quia, nulla! Maiores et perferendis eaque, exercitationem praesentium nihil.
        </p>
        <button class="inline-block mr-3 mt-5 br-3 bw-0 px-3 py-2 fs-s2 bg-gray-lighter black pointer hover-bg-gray-light">Read
        More</button>
    </div>
</div>
```

<div class="flex justify-around">
    <div class="w-33pc br-8 shadow-2 m-3">
        <img class="br-t-8 w-100pc h-auto" src="https://images.unsplash.com/photo-1568960901097-6df09601f134?auto=format&amp;fit=crop&amp;w=800&amp;q=60" alt="" srcset="">
        <div class="p-5">
            <h2 class="gray-light fs-m2 fw-600">Card Without Border</h2>
            <p class="my-3 lh-3 gray-lighter opacity-60">Lorem ipsum dolor sit amet, consectetur adipisicing elit.
            Voluptatibus quia, nulla! Maiores et perferendis eaque, exercitationem praesentium nihil.
            </p>
            <button class="inline-block mr-3 mt-5 br-3 bw-0 px-3 py-2 fs-s2 bg-gray-lighter black pointer hover-bg-gray-light">Read
            More</button>
        </div>
    </div>
    <div class="w-33pc br-8 shadow-1 border-gray m-3">
        <img class="br-t-8 w-100pc h-auto" src="https://images.unsplash.com/photo-1568960901097-6df09601f134?auto=format&amp;fit=crop&amp;w=800&amp;q=60" alt="" srcset="">
        <div class="p-5">
            <h2 class="gray-light fs-m2 fw-600">Card With Border</h2>
            <p class="my-3 lh-3 gray-lighter opacity-60">Lorem ipsum dolor sit amet, consectetur adipisicing elit.
            Voluptatibus quia, nulla! Maiores et perferendis eaque, exercitationem praesentium nihil.
            </p>
            <button class="inline-block mr-3 mt-5 br-3 bw-0 px-3 py-2 fs-s2 bg-gray-lighter black pointer hover-bg-gray-light">Read
            More</button>
        </div>
    </div>
    <div class="w-33pc br-8 bg-blue border-blue m-3">
        <img class="br-t-8 w-100pc h-auto" src="https://images.unsplash.com/photo-1568960901097-6df09601f134?auto=format&amp;fit=crop&amp;w=800&amp;q=60" alt="" srcset="">
        <div class="p-5">
            <h2 class="gray-light fs-m2 fw-600">Colored Background</h2>
            <p class="my-3 lh-3 gray-lighter opacity-60">Lorem ipsum dolor sit amet, consectetur adipisicing elit.
            Voluptatibus quia, nulla! Maiores et perferendis eaque, exercitationem praesentium nihil.
            </p>
            <button class="inline-block mr-3 mt-5 br-3 bw-0 px-3 py-2 fs-s2 bg-gray-lighter black pointer hover-bg-gray-light">Read
            More</button>
        </div>
    </div>
</div>

## Card with header and footer

```html
    <div class="w-33pc br-8 shadow-2 m-3">
        <div class="p-5 br-t-8 bg-gray-light">
            <h2 class="gray-darkest fs-m1 fw-400">Card Without Border</h2>
        </div>
        <div class="p-5">
            <p class="my-3 lh-3 gray-lighter opacity-60">Lorem ipsum dolor sit amet, consectetur adipisicing elit.
            Voluptatibus quia, nulla! Maiores et perferendis eaque, exercitationem praesentium nihil.
            </p>
        </div>
        <div class="flex justify-between p-5 br-b-8 border-t bc-gray-light">
            <button class="inline-block br-3 bw-0 px-3 py-2 fs-s2 bg-blue-darker white pointer hover-opacity-80">Read
            More</button>
            <button class="inline-block br-3 bw-0 px-3 py-2 fs-s2 bg-gray-lighter black pointer hover-opacity-80">Cancel</button>
        </div>
    </div>
    <div class="w-33pc br-8 shadow-1 border-gray m-3">
        <div class="p-5 br-t-8 bg-gray-light">
            <h2 class="gray-darkest fs-m1 fw-400">Card With Border</h2>
        </div>
        <div class="p-5">
            <p class="my-3 lh-3 gray-lighter opacity-60">Lorem ipsum dolor sit amet, consectetur adipisicing elit.
            Voluptatibus quia, nulla! Maiores et perferendis eaque, exercitationem praesentium nihil.
            </p>
        </div>
        <div class="flex justify-between p-5 br-b-8 border-t bc-gray-light">
            <button class="inline-block br-3 bw-0 px-3 py-2 fs-s2 bg-blue-darker white pointer hover-opacity-80">Read
            More</button>
            <button class="inline-block br-3 bw-0 px-3 py-2 fs-s2 bg-gray-lighter black pointer hover-opacity-80">Cancel</button>
        </div>
    </div>
    <div class="w-33pc br-8 bg-blue border-blue m-3">
        <div class="p-5 br-t-8 bg-blue-dark">
            <h2 class="gray-lightest fs-m1 fw-400">Colored Background</h2>
        </div>
        <div class="p-5">
            <p class="my-3 lh-3 gray-lighter opacity-60">Lorem ipsum dolor sit amet, consectetur adipisicing elit.
            Voluptatibus quia, nulla! Maiores et perferendis eaque, exercitationem praesentium nihil.
            </p>
        </div>
        <div class="flex justify-between p-5 br-b-8 border-t bc-gray-light">
            <button class="inline-block br-3 bw-0 px-3 py-2 fs-s2 bg-blue-darker white pointer hover-opacity-80">Read
            More</button>
            <button class="inline-block br-3 bw-0 px-3 py-2 fs-s2 bg-gray-lighter black pointer hover-opacity-80">Cancel</button>
        </div>
    </div>
```

<div class="flex justify-around">
    <div class="w-33pc br-8 shadow-2 m-3">
        <div class="p-5 br-t-8 bg-gray-light">
            <h2 class="gray-darkest fs-m1 fw-400">Card Without Border</h2>
        </div>
        <div class="p-5">
            <p class="my-3 lh-3 gray-lighter opacity-60">Lorem ipsum dolor sit amet, consectetur adipisicing elit.
            Voluptatibus quia, nulla! Maiores et perferendis eaque, exercitationem praesentium nihil.
            </p>
        </div>
        <div class="flex justify-between p-5 br-b-8 border-t bc-gray-light">
            <button class="inline-block br-3 bw-0 px-3 py-2 fs-s2 bg-blue-darker white pointer hover-opacity-80">Read
            More</button>
            <button class="inline-block br-3 bw-0 px-3 py-2 fs-s2 bg-gray-lighter black pointer hover-opacity-80">Cancel</button>
        </div>
    </div>
    <div class="w-33pc br-8 shadow-1 border-gray m-3">
        <div class="p-5 br-t-8 bg-gray-light">
            <h2 class="gray-darkest fs-m1 fw-400">Card With Border</h2>
        </div>
        <div class="p-5">
            <p class="my-3 lh-3 gray-lighter opacity-60">Lorem ipsum dolor sit amet, consectetur adipisicing elit.
            Voluptatibus quia, nulla! Maiores et perferendis eaque, exercitationem praesentium nihil.
            </p>
        </div>
        <div class="flex justify-between p-5 br-b-8 border-t bc-gray-light">
            <button class="inline-block br-3 bw-0 px-3 py-2 fs-s2 bg-blue-darker white pointer hover-opacity-80">Read
            More</button>
            <button class="inline-block br-3 bw-0 px-3 py-2 fs-s2 bg-gray-lighter black pointer hover-opacity-80">Cancel</button>
        </div>
    </div>
    <div class="w-33pc br-8 bg-blue border-blue m-3">
        <div class="p-5 br-t-8 bg-blue-dark">
            <h2 class="gray-lightest fs-m1 fw-400">Colored Background</h2>
        </div>
        <div class="p-5">
            <p class="my-3 lh-3 gray-lighter opacity-60">Lorem ipsum dolor sit amet, consectetur adipisicing elit.
            Voluptatibus quia, nulla! Maiores et perferendis eaque, exercitationem praesentium nihil.
            </p>
        </div>
        <div class="flex justify-between p-5 br-b-8 border-t bc-gray-light">
            <button class="inline-block br-3 bw-0 px-3 py-2 fs-s2 bg-blue-darker white pointer hover-opacity-80">Read
            More</button>
            <button class="inline-block br-3 bw-0 px-3 py-2 fs-s2 bg-gray-lighter black pointer hover-opacity-80">Cancel</button>
        </div>
    </div>
</div>

## Card with background image

```html
<div class="w-33pc m-3 relative">
    <img class="block shadow-3 br-8 w-100pc h-auto" src="https://images.unsplash.com/photo-1568960901097-6df09601f134?auto=format&amp;fit=crop&amp;w=800&amp;q=60" alt="" srcset="">
    <div class="p-5 absolute br-8 top-0 right-0 bottom-0 left-0 bg-black-50">
        <h2 class="white fs-m2 fw-600">Card With Background Image</h2>
        <p class="my-3 lh-3 white opacity-80">Lorem ipsum dolor sit amet, consectetur adipisicing elit.
        Voluptatibus quia, nulla! Maiores et perferendis eaque, exercitationem praesentium nihil.
        </p>
        <button class="inline-block mr-3 mt-5 br-3 bw-0 px-3 py-2 fs-s2 bg-gray-lighter black pointer hover-bg-gray-light">Read
        More</button>
    </div>
</div>
```

<div clall="inline-flex justify-around items-start">
    <div class="w-33pc m-3 relative">
        <img class="block shadow-3 br-8 w-100pc h-auto" src="https://images.unsplash.com/photo-1568960901097-6df09601f134?auto=format&amp;fit=crop&amp;w=800&amp;q=60" alt="" srcset="">
        <div class="p-5 absolute br-8 top-0 right-0 bottom-0 left-0 bg-black-50">
            <h2 class="white fs-m2 fw-600">Card With Background Image</h2>
            <p class="my-3 lh-3 white opacity-80">Lorem ipsum dolor sit amet, consectetur adipisicing elit.
            Voluptatibus quia, nulla! Maiores et perferendis eaque, exercitationem praesentium nihil.
            </p>
            <button class="inline-block mr-3 mt-5 br-3 bw-0 px-3 py-2 fs-s2 bg-gray-lighter black pointer hover-bg-gray-light">Read
        More</button>
        </div>
    </div>
</div>

## Card with aside image

```html
<div class="w-75pc br-8 border-blue m-3 flex items-stretch">
    <div class="w-33pc bg-cover br-l-8" style="background-image:url(https://images.unsplash.com/photo-1568960901097-6df09601f134?auto=format&amp;fit=crop&amp;w=800&amp;q=60);">
    </div>
    <div class="w-66pc p-5">
        <h2 class="gray-lighter fs-m2 fw-600">Card Without Border</h2>
        <p class="my-3 lh-3 gray-light opacity-60">Lorem ipsum dolor sit amet, consectetur adipisicing elit.
        Voluptatibus quia, nulla! Maiores et perferendis eaque, exercitationem praesentium nihil.
        </p>
        <button class="inline-block mr-3 mt-5 br-3 bw-0 px-3 py-2 fs-s2 bg-gray-lighter black pointer hover-bg-gray-light">Read
    More</button>
    </div>
</div>
```

<div class="flex">
    <div class="w-75pc br-8 border-blue m-3 flex items-stretch">
        <div class="w-33pc bg-cover br-l-8" style="background-image:url(https://images.unsplash.com/photo-1568960901097-6df09601f134?auto=format&amp;fit=crop&amp;w=800&amp;q=60);">
        </div>
        <div class="w-66pc p-5">
            <h2 class="gray-lighter fs-m2 fw-600">Card Without Border</h2>
            <p class="my-3 lh-3 gray-light opacity-60">Lorem ipsum dolor sit amet, consectetur adipisicing elit.
            Voluptatibus quia, nulla! Maiores et perferendis eaque, exercitationem praesentium nihil.
            </p>
            <button class="inline-block mr-3 mt-5 br-3 bw-0 px-3 py-2 fs-s2 bg-gray-lighter black pointer hover-bg-gray-light">Read
        More</button>
        </div>
    </div>
</div>