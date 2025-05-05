# python-problem-set-8-solved
**TO GET THIS SOLUTION VISIT:** [Python Problem Set 8 Solved](https://www.ankitcodinghub.com/product/python-problem-set-8-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;99654&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Python Problem Set 8 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
# Problem Set 8

## Overview

This problem set explores three algorithms for solving 3-coloring:

– Exhaustive search

– Augmentation of 2-coloring algorithm with independent sets (covered in Active Learning)

– Reduction to SAT

We have implemented exhaustive search for you as a benchmark. You will implement the augmentation of the 2-coloring algorithm in parts 1a and 1b, and the reduction to SAT in 1c. In 1d, you will compare the performance of these three algorithms.

*Make sure to pull from the course source often or check Ed for updates. We hope to release a perfect problem set but sometimes we add to the problem set to make things easier or fix obscure bugs.*

## Instructions

**Problem 1a**: First, implement the O(n+m)-time algorithm for 2-coloring that we covered in class, verifying its correctness by running `python3 -m ps8_tests 2`. You will need to adapt the given BFS pseudocode so that it works on all graphs, regardless of whether they are connected.

**Problem 1b**: Implement the O(1.89^n)-time algorithm for 3-coloring that you studied in Active Learning Exercise 5, also verifying its correctness by running `python3 -m ps8_tests 3`.

**Problem 1c**: Finally, implement the reduction from 3-coloring to SAT given in class, producing an input that can be fed into the SAT Solver Glucose, and verify its correctness by running `python3 -m ps8_tests 3`.

**Problem 1d**: Compare the performance of the three 3-coloring algorithms on different types of graphs. We have provided most of experiment code in `ps8_experiments.py`; all you have to do is try different parameters and analyze the results.

**Conclusion**: If your work passes the local tests, includes the figure for your generated chart, and answers 1b, you should be in good shape to get full marks for this problem.

You can check that you pass all tests by running `python3 -m ps8_tests`.

## Running the Code

The problem set includes some starter code in `ps8.py`. To run the code, type in your terminal:

“`bash

python3 -m ps8

“`

## Running the Included Tests

The problem set also includes some tests for you to test your code.

To run the tests, type in your terminal:

“`bash

python3 -m ps8_tests 2

“`

“`bash

python3 -m ps8_tests 3

“`

“`bash

python3 -m ps8_experiments

“`
