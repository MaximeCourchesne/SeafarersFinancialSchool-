---
title: The 3-D coordinate system
date: 2024-10-05 16:24:30 -0400
categories: [math,calculusIII]
tags: []     # TAG names should always be lowercase
math: true
---
# 3-D Coordinate System and Applications

The **3-D coordinate system** extends our understanding of the plane ($\mathbb{R}^2$) into three dimensions ($\mathbb{R}^3$), allowing for the representation of points using an additional $z$-coordinate. The **axes**—denoted as $x$, $y$, and $z$—help locate points in space. Points in $\mathbb{R}^3$ can be represented as $P = (x, y, z)$, and their projections onto the coordinate planes are important for understanding spatial relationships.

## Basic Notation

- **$\mathbb{R}^1$**: 1-D line, points represented by $x$-coordinate.
- **$\mathbb{R}^2$**: 2-D plane, points represented by $(x, y)$.
- **$\mathbb{R}^3$**: 3-D space, points represented by $(x, y, z)$.

## Coordinate Planes

- **$xy$-plane**: All points where $z = 0$.
- **$xz$-plane**: All points where $y = 0$.
- **$yz$-plane**: All points where $x = 0$.

## Distance Formula

In $\mathbb{R}^2$, the distance between two points $P_1 = (x_1, y_1)$ and $P_2 = (x_2, y_2)$ is given by:

$$
d(P_1, P_2) = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2}
$$

In $\mathbb{R}^3$, this extends to include the $z$-coordinate:

$$
d(P_1, P_2) = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2 + (z_2 - z_1)^2}
$$

## Equations of Shapes

- **Circle** in $\mathbb{R}^2$ with center $(h, k)$ and radius $r$:

$$
(x - h)^2 + (y - k)^2 = r^2
$$

- **Sphere** in $\mathbb{R}^3$ with center $(h, k, l)$ and radius $r$:

$$
(x - h)^2 + (y - k)^2 + (z - l)^2 = r^2
$$

## Example: Graphing in $\mathbb{R}^n$

- **$x = 3$** in $\mathbb{R}^1$ is a point.
- In $\mathbb{R}^2$, $x = 3$ is a vertical line.
- In $\mathbb{R}^3$, $x = 3$ defines a plane parallel to the $yz$-plane.
![img-description](../images\2024-10-05-math_review_graph\math_review_graph0.png)


## Example 2: A Line Equation

Consider $y = 2x - 3$.

- In $\mathbb{R}^2$, this represents a straight line.
- In $\mathbb{R}^3$, this describes a plane of all points satisfying $y = 2x - 3$ regardless of $z$.
![img-description](../images\2024-10-05-math_review_graph\math_review_graph1.png)

## Graphing a Circle in $\mathbb{R}^3$

In $\mathbb{R}^2$, $x^2 + y^2 = 4$ represents a circle. To graph this in $\mathbb{R}^3$, we must specify a $z$-value, for example $z = 5$. This results in a circle in the plane at $z = 5$.
![img-description](../images\2024-10-05-math_review_graph\math_review_graph2.png)

## Applications in Finance and Economics

Coordinate systems are used in **finance** and **economics** to model multi-variable systems such as:

- **Portfolio optimization**: Uses a multi-dimensional space where each axis represents a different asset. The goal is to maximize returns while minimizing risk, which can be represented as a vector or point in $\mathbb{R}^n$.
- **Economics**: Supply and demand curves in 3D help visualize how changes in one variable (e.g., income) affect the price and quantity in a market.
