# Golden Door

```template
input.onPinPressed(TouchPin.P0, function () {
     
})
```

## Introduction @unplugged

This tutorial will help you solve your first microbit mystery!

<!-- > ## Step 1 @fullscreen

Drag an 'on Pin0 pressed' block into the work area.

```blocks
input.onPinPressed(TouchPin.P0, function () {
     
})
```
-->

## Step 1 

We need to write code to check whether the user is correct if they touch pin #0.

Put a 'check door' custom block inside of the 'on Pin0 pressed' block that's already on your screen.

```blocks
input.onPinPressed(TouchPin.P0, function () {
    custom.checkDoor(0)
})
```

## Step 2 

Let's write some code to check pin #1.
Do the same thing that we did for P0, but make sure you're checking door 1.

```blocks
input.onPinPressed(TouchPin.P1, function () {
    custom.checkDoor(1)
})
```

## Step 3 

Do the same thing for P2, but check door 2.

```blocks
input.onPinPressed(TouchPin.P2, function () {
    custom.checkDoor(2)
})
```

## Step 4

Did writing this code help you figure out what you need to do to solve the mystery?

Try running the code here and see if you can answer the mystery!  

For extra fun, click ``|Download|`` to transfer your code to your microbit!
