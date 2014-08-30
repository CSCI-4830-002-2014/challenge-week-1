# Name

Dawson Botsford

# How many points have you earned?

0/100

(Make your own calculation and replace the number 0 with the points you think you've earned.)

# Show and tell (5 points)

[Dropbox Caught Between Warring Giants Amazon and Google](http://hardware-beta.slashdot.org/story/14/08/25/0130226/dropbox-caught-between-warring-giants-amazon-and-google)

# Splunk

## Checkpoint 1 (10 points)

![image](http://i.imgur.com/Fipt7Uy.png)

## Checkpoint 2 (10 points)

![image](http://i.imgur.com/xlzjgdB.png)

# D3

## Checkpoint 1 (10 points)

![image](http://i.imgur.com/9D6oDU7.png)

## Checkpoint 2 (10 points)

![image](http://i.imgur.com/I05OXxY.png)

## Study Questions (5 points x 3 = 15 points)

### Q1. (5 points)
What would happen if the data’s heading reads differently, like below? Where in the code do you need to modify to get it to work again?

If we change the name of the headings, no chart is rendered due to naming issues. In order to fix this and create a graph, we need to change all occurances of "value" to "count" within the JavaScript code. This is because their is no longer a column titled "value" to reference.

### Q2. (5 points)
What is the point of going through so much trouble to use D3 to make a barchart? Why don’t we just use Excel? What are the benefits of using D3?

D3 is superior to Excel in many ways. Just a few being that we can use the power of HTML, CSS, and SVG to create more unique looking displays. In addition to simple aesthetic differences, D3 allows for web integration in ways that Excel never can since it is a Windows proprietary software. Another great reason to stick with D3 from their GitHub wiki: "D3 is tested against Firefox, Chrome, Safari, Opera, IE9+, Android and iOS." How can Excel even come close to that!? It cannot, that is why D3 is better for dynamic web work as well as many other uses.

### Q3. (5 points)
What is the purpose of the second argument type?

This second value in the ".tsv" function call is for an [accessor function](https://github.com/mbostock/d3/wiki/CSV#tsv). If we look at the bottom of my code, you see the function called "type". This function converts the inputted string to a number. This number conversion is not necessary, but it is very important if we want to do any type of manipulation or sorting, because we need JS to recognize these values as numbers in order to find things like max, sorting, or adding of any kind. 


## Challenge 1 (5 points)

![image](http://i.imgur.com/6blkYp3.png)

[JSFiddle Link](http://jsfiddle.net/L7o0fsas/)

## Challenge 2 (5 points x 7 = 35 points)

### a. 

![image](http://i.imgur.com/KfjLTrT.png)

[JSFiddle Link](http://jsfiddle.net/L7o0fsas/1/h)

### b.

![image](image.png?raw=true)

[JSFiddle Link](http://jsfiddle.net/replace-this-path)

### c.

![image](image.png?raw=true)

[JSFiddle Link](http://jsfiddle.net/replace-this-path)

### d.

![image](image.png?raw=true)

[JSFiddle Link](http://jsfiddle.net/replace-this-path)

### e.

![image](image.png?raw=true)

[JSFiddle Link](http://jsfiddle.net/replace-this-path)

### f.

![image](image.png?raw=true)

[JSFiddle Link](http://jsfiddle.net/replace-this-path)


### g.

![image](image.png?raw=true)

[JSFiddle Link](http://jsfiddle.net/replace-this-path)
