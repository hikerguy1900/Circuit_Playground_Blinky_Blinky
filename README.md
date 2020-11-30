# Blinky Blinky

## Introduction
Let's program! This tutorial will guide you through creating
a program for the Circuit Playground Express. The tutorial was
written for parents and children. Once you've finished this
tutorial I hope you feel confident to experiment with your
own programs. To get started click "Next" to the right.

## Step 1
From the ``||light:Light||`` category on the left, get a
``||light.showRing||`` block. Drag it inside of the
``||loops.forever||`` block that is already in your 
workspace. For a hint, click on the picture of the owl to
the left.
```blocks
    forever(function () {
        light.showRing(
            "red red red red red red red red red red"
        )
    })
```

## Step 2
From the ``||loops:Loops||`` category, get a
``||loops:pause||`` block. Put it after the
``||light.showRing||`` block.
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
## Step 4
From the ``||light:light||`` category, get a
``||light.clear||`` block. Place it after the
pause block.
```blocks
    forever(function () {
        light.showRing(
            "red red red red red red red red red red"
        )
        pause(2000)
        light.clear()
    })
```
## Step 5
From the ``||loops:Loops||`` category, drag a
``||loops:pause||`` block  and place it after your
``||light.clear||`` block. Next change the pause
time from 100 ms to 2 second (2000 ms).
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
## Step 6
To the right you should see a picture of a Circuit Playground
Express. The lights should be blinking just as your program
instructed them to. This is called a simulator. Running your
program in the simulator is a great way to test it.

## Step 7
Below the picture of the Circuit Playground Express
is a row of gray buttons. The left most button stops or
starts the simulator. Give it a try.

## Step 8
We can even use the simulator to see which block is running.
To do this enable, "Slow-Mo", mode by clicking on the Snail
icon. The yellow outline shows you which block of your
programming is active.

## Step 9
Now that you've seen your program working in the simulator let's
download it to the Circuit Playground Express.

## Step 10
Click the big Download button and remember where your computer
downloaded the file to. Follow the instructions that pop-up to
put the program onto your Circuit Playground Expresss.

## Finish
You did it! You've made, simulated, and downloaded your first
program. Nice work! Once you click finish you'll get full 
access to all of the Circuit Playground Express blocks. Click
the, "Home", button in the upper left hand corner of your screen
to go to a list of your projects and other tutorials.