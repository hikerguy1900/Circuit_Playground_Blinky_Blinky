# Blinky Blinky

## Introduction @fullscreen
Let's program! This tutorial will guide you through creating
a program for the Circuit Playground Express. The tutorial was
written for parents and children. Once you've finished this
tutorial I hope you feel confident to experiment with your
own programs. To get started click "Next" to the right.

## Step 1
Get a ``||light.showRing()||`` block from ``||light:Light||``
and place it inside of the ``||loops.forever()||`` block. 
```blocks
    forever(function () {
        light.showRing(
            "red red red red red red red red red red"
        )
    })
```

## Step 2
Drag a ``||loops:pause||`` block from ``||loops:Loops||`` and
place it after your ``||light.showRing()||`` block.
```blocks
    forever(function () {
        light.showRing(
            "red red red red red red red red red red"
        )
        pause(100)
    })
```
## Step 3
Change the pause time from 100 ms to 2 seconds (2000 ms).
```blocks
    forever(function () {
        light.showRing(
            "red red red red red red red red red red"
        )
        pause(2000)
    })
```
## Step 3
Get at ``||light.clear()||`` block from ``||light:light||``
and place it after the pause block.

```blocks
    forever(function () {
        light.showRing(
            "red red red red red red red red red red"
        )
        pause(2000)
        light.clear()
    })
```
## Step 4
Drag a ``||loops:pause||`` block from ``||loops:Loops||`` and
place it after your ``||light.clear()||`` block. Next change
the pause time from 100 ms to 2 second (2000 ms).

```blocks
    forever(function () {
        light.showRing(
            "red red red red red red red red red red"
        )
        pause(2000)
        light.clear()
        pause(2000)
    })
```
## Step 5
To the right you should see your lights blinking. This is our
simulator. Use the left most button to stop and start the
simulator. Give it a try.

## Step 6
Running your program in the simulator is a great way to test it.
We can even use the simulator to see which block is running. To do 
this enable Slow-Mo mode by click on the Snail icon below the
Circuit Playground picture. The yellow outline shows you which
block of your programming is active.

## Step 7
Now that we've seen our program working in the simulator let's
download it to the Circuit Playground.

## Step 8
Click the big Download button and remember where your computer
downloaded the file to.

## Step 9
Plug in your circuit playground to your computer. The circuit 
playground should show up as a new driver named "CPLAY".

## Step 10
Drag the file you downloaded in step 8 to the "CPLAY" drive.


> Open this page at [https://hikerguy1900.github.io/circuit_playground_blinky_blinky/](https://hikerguy1900.github.io/circuit_playground_blinky_blinky/)

## Use as Extension

This repository can be added as an **extension** in MakeCode.

* open [https://makecode.adafruit.com/](https://makecode.adafruit.com/)
* click on **New Project**
* click on **Extensions** under the gearwheel menu
* search for **https://github.com/hikerguy1900/circuit_playground_blinky_blinky** and import

## Edit this project ![Build status badge](https://github.com/hikerguy1900/circuit_playground_blinky_blinky/workflows/MakeCode/badge.svg)

To edit this repository in MakeCode.

* open [https://makecode.adafruit.com/](https://makecode.adafruit.com/)
* click on **Import** then click on **Import URL**
* paste **https://github.com/hikerguy1900/circuit_playground_blinky_blinky** and click import

## Blocks preview

This image shows the blocks code from the last commit in master.
This image may take a few minutes to refresh.

![A rendered view of the blocks](https://github.com/hikerguy1900/circuit_playground_blinky_blinky/raw/master/.github/makecode/blocks.png)

#### Metadata (used for search, rendering)

* for PXT/adafruit
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
