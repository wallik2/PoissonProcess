<p align="center">
  <a href="https://example.com/">
    <img src="http://24.media.tumblr.com/2a36ba2a3016572f698ec19ad0051a39/tumblr_mrg3g8Nkbx1swdfc0o1_500.gif" alt="Logo" width=300 height=300>
  </a>

  <h3 align="center">Poisson Process</h3>

  <p align="center">
    The guided Jupyter notebook helps to bring you an automation sense of creating the poisson process. 
    <br>
    This jupyter notebook is based on the following two lecture videos by MIT
    <br>
    <a href="https://www.youtube.com/watch?v=jsqSScywvMc">Lecture Part 1</a>
    ·
    <a href="https://www.youtube.com/watch?v=XsYXACeIklU">Lecture Part 2</a>
  </p>
</p>

[![open in colab](https://camo.githubusercontent.com/52feade06f2fecbf006889a904d221e6a730c194/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/github/wallik2/PoissonProcess/blob/master/Poisson_process.ipynb)


---

## Table of contents

- [Quick start](#quick-start)
- [Ingredients](#ingredients)
- [Fundamental of what](#Fundamental-of-what)

## Quick start

Poisson process is used to explain many events in a real life that involved in the count number (integer) 

Eg. The number of car that run though your village today

![](https://raw.githubusercontent.com/axelpale/poisson-process/HEAD/doc/cars.gif?raw=true)

What set the poisson process so special is it can be used to throughly observe the number of count within an extremely small interval (**δ**). 

Note that the Poisson process assume the only possible number of count within that extremely small interval is 0 or 1 (which makes sense for most of the cases). 

Thus, when you want the number of count within the any given time period (**t**). is just the summation of all counts of many δ 

---
## Ingredients

Soooo, what do you need to make a poisson process, 


 <h3> 1. λ : The arrival rate (per time unit τ) </h3>
 
- The higher λ, the high chance that within an extremely interval will have  1 occurence is higher

<h3> 2. δ : An extremely small interval</h3> 

- Huh ? you may ask why do we need it when we already know its value closes to zero.
<br>In Programming Language, It can cause underflow. so we have to fix the most possible smallest value that you can set


With the given *λ*, you can obtain the insights from the poisson process with any *t* you want

- The **Probability that have k occurences at t**
- The **Interarrival time** (High λ, should have low Interarrival time)


---

## Fundamental of what

One of the notable stuffs that need Poisson process as the fundamental is called **Markov process**

Another name for Markov process is called **Continuous Markov chain**.

The issue of Discrete markov chain is its arbitraty time make it unable to capture true transition rate, 

Hence, Poisson process came here helping to solve this problem by is using an extremely small interval called **δ**. (Arbitrary **t** problem is solved!), and then it's how the Markov process occurs !!


<h2>Check the notebook for dive deeper on how I automate the poisson process using just Python</h2>
