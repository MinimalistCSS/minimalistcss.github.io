---
title: Modal
weight: 30
---

This modal is an example created using classes. There is no class of modal box

<div class="bg-gray-lightest gray-darkest px-5 py-3 br-3 border-l bw-6 bc-gray">
    <p>
        <span class="hljs-keyword">.modal</span> class and <span class="fw-600"> jquery</span> used in this example is not a part of the framework. We used it for demonstration purpose only. You can either use it or can write your own.
    </p>
</div>

## Examples

```html
<!-- modal button -->
<button class="button" data-toggle="modal" data-target="#modal-one">Open Modal</button>
 <!-- modal -->
 <div id="modal-one" class="modal hidden absolute-full fixed z-10000 bg-black-50 ease-900">
    <div class="bg-white mx-auto mt-l5 w-50pc border br-8 overflow-hidden">
        <div class="px-5 py-3 bg-gray-lightest flex justify-between items-center border-b">
            <h3 class="black opacity-80">Title</h3>
            <button data-dismiss="modal" class="button p-0 bg-transparent gray after-times-large"></button>
        </div>
        <div class="px-5 py-10 fs-s1">
            This is an awesome modal box.
        </div>
        <div class="px-5 py-3 border-t flex justify-between items-center">
            <button data-dismiss="modal" class="button bg-black">I Agree</button>
            <button data-dismiss="modal" class="button bg-gray-lightest gray"> close</button>
        </div>
    </div>
</div>
<!-- jquery to open and close modal-->
<script>
    $(document).on('click', '[data-toggle=modal]', function () {
        $($(this).attr('data-target')).toggleClass('hidden');
    });
    $(document).on('click', '[data-dismiss=modal]', function () {
        $(this).closest('.modal').toggleClass('hidden');
    });
</script>
```

<!-- modal button -->
<button class="button" data-toggle="modal-one" data-target="#modal-one">Open Modal</button>
 <!-- modal -->
 <div id="modal-one" class="modal hidden absolute-full fixed z-10000 bg-black-50 ease-900">
    <div class="bg-white mx-auto mt-l5 w-50pc border br-8 overflow-hidden">
        <div class="px-5 py-3 bg-gray-lightest flex justify-between items-center border-b">
            <h3 class="black opacity-80">Title</h3>
            <button data-dismiss="modal" class="button p-0 bg-transparent gray after-times-large"></button>
        </div>
        <div class="px-5 py-10 fs-s1">
            This is an awesome modal box.
        </div>
        <div class="px-5 py-3 border-t flex justify-between items-center">
            <button data-dismiss="modal" class="button bg-black">I Agree</button>
            <button data-dismiss="modal" class="button bg-gray-lightest gray"> close</button>
        </div>
    </div>
</div>
<!-- jquery to open and close modal-->
<script>
    $(document).on('click', '[data-toggle=modal-one]', function () {
        $($(this).attr('data-target')).toggleClass('hidden');
    });
    $(document).on('click', '[data-dismiss=modal-one]', function () {
        $(this).closest('.modal').toggleClass('hidden');
    });
</script>

```html
<!-- modal button -->
<button class="button" data-toggle="modal-two" data-target="#modal-two">Open Modal</button>
 <!-- modal -->
 <div id="modal-two" class="modal hidden absolute-full fixed z-1000 bg-black-50 ease-900">
    <div class="relative bg-white mx-auto mt-l5 w-90pc md-w-50pc border br-8 overflow-hidden">
            <button data-dismiss="modal" class="absolute button p-0 m-4 top-0 right-0 bg-transparent indigo-lighter fs-l2 lh-0 flex justify-center fw-100">&times;</button>
        <div class="px-3 py-10 md-px-10 md-py-l5">
        <div class="fs-s1 text-center w-70pc mx-auto">
            <h3 class="fs-m5 my-3 indigo-darkest fw-400">Subscribe to newsletter</h3>
            <p class="black opacity-70 lh-5">We're giving away a free product to every 10th subscriber. Subscribe to enter the giveaway.
            </p>
        </div>
        <div class="px-5 py-3 w-80pc mx-auto text-center">
            <input class="input-lg full my-4 fs-s2 br-0" type="email" placeholder="Email Address">
            <button class="button-lg full bg-indigo fs-s2 br-0">Subscribe</button>
        </div>
    </div>
    </div>
</div>
<!-- jquery to open and close modal-->
<script>
    $(document).on('click', '[data-toggle=modal-two]', function () {
        $($(this).attr('data-target')).toggleClass('hidden');
    });
    $(document).on('click', '[data-dismiss=modal-two]', function () {
        $(this).closest('.modal').toggleClass('hidden');
    });
</script>
```

<!-- modal button -->
<button class="button" data-toggle="modal-two" data-target="#modal-two">Open Modal</button>
 <!-- modal -->
 <div id="modal-two" class="modal hidden absolute-full fixed z-1000 bg-black-50 ease-900">
    <div class="relative bg-white mx-auto mt-l5 w-90pc md-w-50pc border br-8 overflow-hidden">
            <button data-dismiss="modal" class="absolute button p-0 m-4 top-0 right-0 bg-transparent indigo-lighter fs-l2 lh-0 flex justify-center fw-100">&times;</button>
        <div class="px-3 py-10 md-px-10 md-py-l5">
        <div class="fs-s1 text-center w-70pc mx-auto">
            <h3 class="fs-m5 my-3 indigo-darkest fw-400">Subscribe to newsletter</h3>
            <p class="black opacity-70 lh-5">We're giving away a free product to every 10th subscriber. Subscribe to enter the giveaway.
            </p>
        </div>
        <div class="px-5 py-3 w-80pc mx-auto text-center">
            <input class="input-lg full my-4 fs-s2 br-0" type="email" placeholder="Email Address">
            <button class="button-lg full bg-indigo fs-s2 br-0">Subscribe</button>
        </div>
    </div>
    </div>
</div>
<!-- jquery to open and close modal-->
<script>
    $(document).on('click', '[data-toggle=modal-two]', function () {
        $($(this).attr('data-target')).toggleClass('hidden');
    });
    $(document).on('click', '[data-dismiss=modal-two]', function () {
        $(this).closest('.modal').toggleClass('hidden');
    });
</script>