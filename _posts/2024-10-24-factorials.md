---
layout: post
title:  "What is the factorial of decimals or negative integers ?"
date:   2024-10-24
categories: jekyll update
---
The value of 5! can be simply calculated as 5×4×3×2×1, and similarly for 7!, the result is 7×6×5×4×3×2×1. 
Special cases such as 0! and 1! are both equal to 1.

This can be generalized as n!=n×(n−1)×(n−2)× … ×1.

While this generalized expression holds true for all positive integers, it becomes challenging when estimating factorials of non-integer values, especially those between 0 and 1. If you think about it, even the approach to calculate (or estimate) 0! maybe be different.

I only realized today that the [gamma function](https://en.wikipedia.org/wiki/Gamma_function) is the way to go for values like these. It’s a more universal approach for calculating the factorial of any real number, including values between 0 and 1, and even negative numbers (excluding non-positive integers where factorials are undefined).

<img src="{{ site.baseurl }}/assets/img/Gamma_plot.png" width="250" style="float:left; margin-right:20px;">
*Credits: Wikipedia* 
