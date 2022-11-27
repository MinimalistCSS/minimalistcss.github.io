---
title: Table
weight: 45
---

Apply all the classes to table container <span class="hljs-keyword">.table-container</span>.

* [head](#head)
* [row border](#row-border)
* [cell border](#cell-border)
* [color](#table-color)



<div class="table-container table-head">
    <table>
        <thead>
            <tr>
                <td>Class</td>
                <td>Utility</td>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td class="hljs-keyword">.table-container</td>
                <td>Sets the border color and width 100%</td>
            </tr>
            <tr>
                <td class="hljs-keyword">.table-head</td>
                <td>Set the color of table head</td>
            </tr>
            <tr>
                <td class="hljs-keyword">.table-striped</td>
                <td>Set background color of alternate row</td>
            </tr>
            <tr>
                <td class="hljs-keyword">.row-border</td>
                <td>Set the border of all rows</td>
            </tr>
            <tr>
                <td class="hljs-keyword">.cell-border</td>
                <td>Set the border of all cells</td>
            </tr>
        </tbody>
    </table>
</div>


## Table Head

Use class <span class="hljs-keyword">.table-head</span>

```html
<div class="table-container table-head">
    <table>
        <thead>
            <tr>
                <td>Col 1</td>
                <td>Col 2</td>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>10</td>
                <td>11</td>
            </tr>
            <tr>
                <td>20</td>
                <td>21</td>
            </tr>
            <tr>
                <td>30</td>
                <td>31</td>
            </tr>
        </tbody>
    </table>
</div>
```

<div class="table-container table-head">
    <table>
        <thead>
            <tr>
                <td>Col 1</td>
                <td>Col 2</td>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>10</td>
                <td>11</td>
            </tr>
            <tr>
                <td>20</td>
                <td>21</td>
            </tr>
            <tr>
                <td>30</td>
                <td>31</td>
            </tr>
        </tbody>
    </table>
</div>

## Row border

Use class <span class="hljs-keyword">.row-border</span>

```html
<div class="table-container table-head row-border">
    <table>
        <thead>
            <tr>
                <td>Col 1</td>
                <td>Col 2</td>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>10</td>
                <td>11</td>
            </tr>
            <tr>
                <td>20</td>
                <td>21</td>
            </tr>
            <tr>
                <td>30</td>
                <td>31</td>
            </tr>
        </tbody>
    </table>
</div>
```

<div class="table-container table-head row-border">
    <table>
        <thead>
            <tr>
                <td>Col 1</td>
                <td>Col 2</td>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>10</td>
                <td>11</td>
            </tr>
            <tr>
                <td>20</td>
                <td>21</td>
            </tr>
            <tr>
                <td>30</td>
                <td>31</td>
            </tr>
        </tbody>
    </table>
</div>

## Cell border

Use class <span class="hljs-keyword">.cell-border</span>

```html
<div class="table-container table-head cell-border">
    <table>
        <thead>
            <tr>
                <td>Col 1</td>
                <td>Col 2</td>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>10</td>
                <td>11</td>
            </tr>
            <tr>
                <td>20</td>
                <td>21</td>
            </tr>
            <tr>
                <td>30</td>
                <td>31</td>
            </tr>
        </tbody>
    </table>
</div>
```

<div class="table-container table-head cell-border">
    <table>
        <thead>
            <tr>
                <td>Col 1</td>
                <td>Col 2</td>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>10</td>
                <td>11</td>
            </tr>
            <tr>
                <td>20</td>
                <td>21</td>
            </tr>
            <tr>
                <td>30</td>
                <td>31</td>
            </tr>
        </tbody>
    </table>
</div>

## Table Color

To change the color of table add background color <span class="hljs-keyword">.bg-slategray</span> , border color <span class="hljs-keyword">.bc-slategray-light</span> and text color <span class="hljs-keyword">.slategray-light</span> style to table tag.

Similarly you can change the color of <span class="hljs-keyword">thead</span>

```html
<div class="table-container text-center cell-border">
    <table class="bg-slategray bc-slategray-light slategray-light">
        <thead class="white bg-slategray-dark">
            <tr>
                <td>Col 1</td>
                <td>Col 2</td>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>10</td>
                <td>11</td>
            </tr>
            <tr>
                <td>20</td>
                <td>21</td>
            </tr>
            <tr>
                <td>30</td>
                <td>31</td>
            </tr>
        </tbody>
    </table>
</div>
```

<div class="table-container text-center cell-border">
    <table class="bg-slategray bc-slategray-light slategray-light">
        <thead class="white bg-slategray-dark">
            <tr>
                <td>Col 1</td>
                <td>Col 2</td>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>10</td>
                <td>11</td>
            </tr>
            <tr>
                <td>20</td>
                <td>21</td>
            </tr>
            <tr>
                <td>30</td>
                <td>31</td>
            </tr>
        </tbody>
    </table>
</div>