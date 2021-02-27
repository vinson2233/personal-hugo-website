+++
date = ""
title = "Numpy and Pandas Numerical Data Types. Stability, Speed and Memory Usage"

+++
What could go wrong if I use float32 instead of float64 ?  
I need more speed for my calculation without changing my code alot, is changing data types coud help me?  
I have limited RAM for processing huge dataset, what does this post means to me ?  
The goal of this post is to answer these question, focusing on speed and precision, without much tough about how it implemented. I’m assuming you to have some familiarity with Python, Numpy and Pandas.

> "If number is a stick, and variable is a hole. Using a big hole to store a small stick is wasteful. What worse is putting a huge stick to a small hole" - Vinson

List of thing we need to consider :

* Numerical Stability
* Speed
* Memory

### Numerical Stability

  
We need to make sure our number calculated correctly. Floating number (in almost every programming language that i know) have some unavoidable inaccuracies. This is the most famous example of such case.

![dddd](https://vinson2233.files.wordpress.com/2020/11/image_2020-11-17_160743.png?w=1024 "ddd")