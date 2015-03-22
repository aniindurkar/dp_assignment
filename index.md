---
title       : Data Products Assignment
subtitle    : Mar 22, 2015
author      : AI
job         : Newbie
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
--- .class #id 

## Slide 2

This is the first Sales Forecasting model developed by the ACME Corp - a widget maker.
The ACME Sales team has a requirement to forecast unit sales for the next quarter in order to assess fixed and variable costs

--- .class #id 

## slide 3

The forecase methodology essentially makes use of the last month sales and allows the user to input the following variables -

1. ACME's growth rate<p>
2. The Industry sector growth rate<p>
3. Business sentiment<p>

The forecast team has arrived at ranges for these three entities based on heuristics which are critical for the model.

--- .class #id 

## slide 4

The ACME Forcasting formula

Let -<p>
ACME Growth rate be 'a'<p>
Sector Growth rate be 's'<p>
Business Sentiment by 'c'<p>
<b>Forecast Factor be 'f'</b><p>

$$f = \sqrt{1 + 1.1 a + 0.3 s + c/10}$$

--- .class #id 

## slide 4

Now if 
Last Known Sales Units be 'q'<p>
And Forecast Sales for the next 3 months be 't1, t2, t3'<p>

$$t1 = q f$$<p>

$$t2 = q f^2$$<p>

$$t3 = q f^3$$<p>

--- .class #id 

## slide 5

<h3> Using the Model</h3>
The Model is very simple to use and is self documenting, the user's input and the output are displayed on a web page<p>

<h4> Pre-requisites </h4>
Prior month data is required for the model to successfully work.<p>
The data is to be stored in a file called "salesqty.csv" in CSV format <p>
The files content is new-line limited records with layout $$(month number, sales units)$$

<h5>For Additional Help</h5>
Pl contact ACME @ 800-555-1212

--- .class #id 

## slide 5

<h1> Thank You </h1>
