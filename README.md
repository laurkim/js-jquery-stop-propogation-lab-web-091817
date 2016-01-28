# Stop Propogation Lab

## Objectives
+ use stopPropogation to prevent event handlers from bubbling up

## Intro

You've been hired to fix some major issues with a traffic light. Your job is to refactor the existing code to make sure that the events firing on the page are only firing them you want them to.



## Instructions

Open up `index.html` in the browser. You should see the outline of 3 traffic lights. When you click on the body of any of the lights, they background of the fixture should turn purple. When you click it again, it should turn white.

When you click on one of the lights, like the top light of the first fixture, the light turns red, but the body turns purple. Click around a bit and take a look at the behavior of the lights.

Ideally, we want to be able to click on the lights and only have that specific light change value. Your job is to edit the code in `js/script.js` to fix up the existing code.

There are tests to make sure that you're on the right track!

