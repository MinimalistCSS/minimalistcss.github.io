---
title: Collapse
weight: 25
---

This collapse is an example created using classes. There is no class of collapse.

<div class="bg-gray-lightest gray-darkest px-5 py-3 br-3 border-l bw-6 bc-gray">
    <p>
        <span class="hljs-keyword">.collapse-trigger</span> and <span class="hljs-keyword">.collapse-target</span> classes and <span class="fw-600"> jquery</span> used in this example is not a part of the framework. We used it for demonstration purpose only. You can either use it or can write your own.
    </p>
</div>

## Examples

```html
<div class="p-5 border br-t-8 mt-5 ">
    <div class="w-80pc mx-auto">
        <div class="collapse-trigger no-underline hover-underline block w-100pc p-5 my-1 br-4 bg-gray-lighter blue after-right after-scale-up-3 after-plus">
        What is Lorem ipsum?</div>
        <div class="collapse-target" style="display: none;">
            <div class="p-5 border br-4">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum
            </div>
        </div>
    </div>
</div>
<!-- jquery -->
<script>
    $('.collapse-target').hide();
    $(document).on('click', '.collapse-trigger', function () {
        $(this).toggleClass('after-plus after-minus');
        $(this).next().slideToggle();
        return false;
    });
</script>
```

<div class="p-5 border br-t-8 mt-5 ">
    <div class="w-80pc mx-auto">
        <div class="collapse-trigger no-underline hover-underline block w-100pc p-5 my-1 br-4 bg-gray-lighter blue after-right after-scale-up-3 after-plus">
        What is Lorem ipsum?</div>
        <div class="collapse-target" style="display: none;">
            <div class="p-5 border br-4">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum
            </div>
        </div>
    </div>
</div>
<!-- jquery -->
<script>
    $('.collapse-target').hide();
    $(document).on('click', '.collapse-trigger', function () {
        $(this).toggleClass('after-plus after-minus');
        $(this).next().slideToggle();
        return false;
    });
</script>

