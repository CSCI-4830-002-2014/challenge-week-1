# Name

Brian Newsom

# How many points have you earned?

100/100

(Make your own calculation and replace the number 0 with the points you think you've earned.)

# Show and tell (5 points)

[Why Small Businesses Actually Have the Big-Data Advantage](http://www.entrepreneur.com/article/236766)

# Splunk

## Checkpoint 1 (10 points)

![image](Checkpoint1.png?raw=true)

## Checkpoint 2 (10 points)

![image](Checkpoint2.png?raw=true)

# D3

## Checkpoint 1 (10 points)

![image](Checkpoint3.png?raw=true)

## Checkpoint 2 (10 points)

![image](Checkpoint4.png?raw=true)

## Study Questions (5 points x 3 = 15 points)

### Q1. (5 points)

The header is changed here.  D3 would have to be altered to interpret the columns correctly.  In this code, only the second column is used, so all usages of "value" should be changed to "count".

### Q2. (5 points)

D3 is much more friendly for a web UI.  From excel (I believe) you would have to export the chart each time something is changed.  D3 is more dynamic in this case.  Additionally, in certain cases it provides advantages over excel in that adding data can be done without parsing the whole document but instead appending what does not already exist.

### Q3. (5 points)

In the given code, the type parameter specifies a callback function that allows you to specify how the data is interpreted.  Here, the data is forced to be a number using the code: 
```
function type(d) {
  d.value = +d.population; // coerce to number
  return d;
}
```
so that it is not interpreted as a string.

## Challenge 1 (5 points)

![image](fiddle3.png?raw=true)

[JSFiddle Link](http://jsfiddle.net/53e9ppcv/3/)

## Challenge 2 (5 points x 7 = 35 points)

### a. 

![image](fiddle4.png?raw=true)

[JSFiddle Link](http://jsfiddle.net/53e9ppcv/4/)

### b.

![image](fiddle5.png?raw=true)

[JSFiddle Link](http://jsfiddle.net/53e9ppcv/5/)

### c.

![image](fiddle6.png?raw=true)

[JSFiddle Link](http://jsfiddle.net/53e9ppcv/6/)

### d.

![image](fiddle7.png?raw=true)

[JSFiddle Link](http://jsfiddle.net/53e9ppcv/7/)

### e.

![image](fiddle8.png?raw=true)

[JSFiddle Link](http://jsfiddle.net/53e9ppcv/8/)

### f.

![image](fiddle9.png?raw=true)

[JSFiddle Link](http://jsfiddle.net/53e9ppcv/9/)


### g.

![image](fiddle10.png?raw=true)

[JSFiddle Link](http://jsfiddle.net/53e9ppcv/10/)
