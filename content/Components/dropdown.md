---
title: Dropdown
weight: 25
---

This dropdown is an example created using classes. There is no class of dropdown.

<div class="bg-gray-lightest gray-darkest px-5 py-3 br-3 border-l bw-6 bc-gray">
    <p>
        <span class="hljs-keyword">.dropdown-menu</span> class and <span class="fw-600"> jquery</span> used in this example is not a part of the framework. We used it for demonstration purpose only. You can either use it or can write your own.
    </p>
</div>

## Examples

```html
<div class="p-5 border br-t-8 mt-5 ">
    <div class="relative inline-block ">
        <a class="button bg-red hover-bg-red-light hover-red-lightest" data-toggle="dropdown">
        Dropdown
        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-chevron-down h-5 ml-1"><polyline points="6 9 12 15 18 9"></polyline></svg>
        </a>
        <div class="dropdown-menu hidden absolute z-100 left-0 top-100pc py-1 fs-s2">
            <div class="shadow-3 br-6 bg-white min-w-l10 border">
                <a class="block p-3 hover-bg-red-lighte red no-underline" href="#">Do this</a>
                <a class="block p-3 hover-bg-red-lighter red no-underline" href="#">Or do this</a>
                <a class="block p-3 hover-bg-red-lighter red no-underline" href="#">DO something else</a>
            </div>
        </div>
    </div>
</div>
<!-- jquery -->
<script>
    $(document).on('click',function(event) {
        $target = $(event.target);
        if(!$target.closest('.dropdown-menu').length && $('.dropdown-menu').is(":visible")) {
            $('.dropdown-menu:visible').toggleClass('hidden');
        }
    });
    $(document).on('click', '[data-toggle=dropdown]', function () {
        $(this).siblings('.dropdown-menu').toggleClass('hidden');
        return false;
    });
    $('.dropdown-menu').on('click',function(event){
        event.stopPropagation();
    });
</script>
```

<div class="p-5 border br-t-8 mt-5 ">
    <div class="relative inline-block ">
        <a class="button bg-red hover-bg-red-light hover-red-lightest" data-toggle="dropdown">
        Dropdown
        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-chevron-down h-5 ml-1"><polyline points="6 9 12 15 18 9"></polyline></svg>
        </a>
        <div class="dropdown-menu hidden absolute z-100 left-0 top-100pc py-1 fs-s2">
            <div class="shadow-3 br-6 bg-white min-w-l10 border">
                <a class="block p-3 hover-bg-red-lighte red no-underline" href="#">Do this</a>
                <a class="block p-3 hover-bg-red-lighter red no-underline" href="#">Or do this</a>
                <a class="block p-3 hover-bg-red-lighter red no-underline" href="#">DO something else</a>
            </div>
        </div>
    </div>
</div>
<!-- jquery -->
<script>
    $(document).on('click',function(event) {
        $target = $(event.target);
        if(!$target.closest('.dropdown-menu').length && $('.dropdown-menu').is(":visible")) {
            $('.dropdown-menu:visible').toggleClass('hidden');
        }
    });
    $(document).on('click', '[data-toggle=dropdown]', function () {
        $(this).siblings('.dropdown-menu').toggleClass('hidden');
        return false;
    });
    $('.dropdown-menu').on('click',function(event){
        event.stopPropagation();
    });
</script>

