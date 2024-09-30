---
title: Syntax for .md files
date: 2024-09-29 16:24:30 -0400
categories: [tech,programming,markdown]
tags: [programming]     # TAG names should always be lowercase
---

# Overview of Jekyll Syntax

# This is an h1
## This is an h2
### This is an h3
#### This is an h4
##### This is an h5

# Sample Test
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus malesuada turpis at nibh dignissim, quis dictum est fringilla. Vestibulum dictum erat lorem, et sodales nunc dapibus vitae. Praesent consectetur molestie dolor, in egestas tellus finibus id. Pellentesque euismod erat sed mauris posuere, quis hendrerit elit interdum. Pellentesque urna magna, elementum at ligula fermentum, ultricies tempor turpis. Nunc sed tellus mollis, placerat odio sed, mollis diam. Nunc gravida blandit metus, nec ultrices orci maximus non. Ut eu bibendum odio, et posuere enim. Etiam auctor pulvinar dictum. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Donec dapibus elit molestie dui scelerisque, molestie aliquet dolor molestie. Integer convallis rutrum convallis. Nam commodo at massa ut euismod. Aliquam eu sem sem. Nam vitae egestas tortor, non convallis nisl.

Etiam a nisi sit amet dolor aliquam porttitor. Nulla semper gravida ipsum eget congue. Integer quis interdum lectus. Pellentesque sed interdum risus. Sed vestibulum ligula et lacus posuere lacinia. Nunc id tortor ut nibh bibendum vestibulum vel in dui. Duis eget semper nisi.

## section title 2
Vestibulum condimentum augue dolor, ut accumsan lectus bibendum sit amet. Nulla imperdiet velit nec ligula posuere pretium. Sed ultricies lorem vel lectus cursus mollis. Etiam sed ultrices nisi, vel tincidunt odio. Nunc quis mollis ligula. Pellentesque justo elit, volutpat nec maximus faucibus, interdum eu turpis. Maecenas porta diam magna, in vestibulum lorem blandit sit amet. Aliquam ullamcorper orci et egestas ornare. Donec diam dui, volutpat sed enim id, malesuada posuere ligula. Nulla rutrum ullamcorper nisl, in posuere nulla gravida ac. Quisque mattis maximus dui, in efficitur nisi vehicula ac. Aliquam eget dictum sapien, quis ornare turpis. Vestibulum id fermentum nunc. Suspendisse in est sit amet lectus tincidunt tempor. Maecenas fermentum commodo mi aliquet commodo. Vivamus condimentum ex lorem.

* one
* two
* three
* four

Quisque elementum turpis sed sapien molestie viverra. Vestibulum suscipit nulla quam, quis convallis risus imperdiet nec. Ut congue, diam vel lobortis pretium, ex ante varius tellus, ut sodales erat ligula vel dolor. Cras sed arcu aliquet, vestibulum massa in, aliquet nisl. Vestibulum eu eros maximus, gravida elit quis, scelerisque nisl. Morbi leo ligula, aliquet id condimentum vel, condimentum non felis. Cras elementum, justo eu porttitor faucibus, libero dolor condimentum leo, non ornare metus lectus eu turpis. Interdum et malesuada fames ac ante ipsum primis in faucibus. Phasellus dapibus est a hendrerit vehicula. Integer auctor euismod magna nec vulputate. Donec vel varius dui. Cras scelerisque nisi sit amet orci pretium, nec convallis risus pretium.

```java
public class RecursiveFibonacci {
    public static int fibonacci(int n) {
        if (n <= 1) {
            return n;
        }
        return fibonacci(n - 1) + fibonacci(n - 2);
    }

    public static void main(String[] args) {
        int n = 10; // nth Fibonacci number we want to calculate
        System.out.println("The " + n + "th Fibonacci number is: " + fibonacci(n));
    }
}
```

## Images
![img-description](../Screenshot%20from%202024-09-29%2016-52-10.png)
_Circuit that takes a small signal Vin and outputs an amplified signal Vout. The input signal frequency is limited by the maximum operation frequency of the BJT (the trasistor)_



Nunc volutpat urna ut vestibulum euismod. Nam lobortis, mi eget ultrices laoreet, ante nibh laoreet sem, sed eleifend purus ante non sem. Nulla imperdiet a leo et placerat. Donec sit amet lectus nec tortor dictum hendrerit. Curabitur commodo auctor lacus in dictum. Maecenas dui dolor, dapibus sit amet lectus non, eleifend varius libero. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Nam et velit non lectus elementum fringilla. Curabitur urna sapien, ultricies non suscipit et, interdum at ante. Phasellus commodo, libero ut ultricies auctor, tortor libero egestas purus, dignissim convallis lorem augue a nibh.

