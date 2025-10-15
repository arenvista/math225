---
id: Homework_4
aliases: []
tags: []
---

# Table of Contents

## Problem 1

Show the given solves IVP:
$$y(x) = c_1e^{2x} + c_2xe^{2x}$$
$$y(0)=0, y'(0)=2$$

---

$$y(x) = c_1e^{2x} + c_2xe^{2x}$$
$$y'(x) = 2c_1e^{2x} + c_2e^{2x} + 2c_2xe^{2x}$$

---
Plug in IC:

$$y(0) = c_1e^{2(0)} + c_2(0)e^{2(0)} = 0$$
$$y(0) = c_1e^{2(0)} + 0$$
$$y(0) = c_1$$
$$y(0) = c_1 = 0$$

$$y'(0) = 2c_1e^{2x} + c_2e^{2x} + 2c_2xe^{2x} = 2$$
$$y'(0) = 2c_1e^{2(0)} + c_2e^{2(0)} + 2c_2(0)e^{2(0)} = 2$$
$$y'(0) = 2c_1 + c_2 + 0 = 2$$
$$y'(0) = 0 + c_2 + 0 = 2$$
$$y'(0) = c_2 = 2$$

$$\therefore c_1 = 0, c_2 = 2$$

## Problem 3

Determine if $\exists ~x! \in [a,b] ~a,b \in \mathbb{R}$ s.t. $f(x)=0$
$$ f(x) = x(x-1)y''+ 2xy' + y = 0$$

$$f(x) ~C[a,b] \implies \exists ~x! \in [a,b] ~a,b \in \mathbb{R} \ni f(x)=0$$

---
$$ f(x) = x(x-1)y''+ 2xy' + y = 0$$
$$ f(x) = y''+ \dfrac{2y'}{x-1} + \dfrac{y}{x(x-1)} = 0$$
$$ f(x) = y''+ \dfrac{1}{x-1}[2y]' + \dfrac{1}{x(x-1)}[y] = 0$$

Observe $f(x)$ C[a,b] so long as $(x-1) \neq 0$ and $x(x-1) \neq 0$

$$x-1 \neq 0$$
$$ x \neq 1 \implies f(x) C(-\infty, 1)$$

$$x(x-1) \neq 0$$
$$ x \neq 1 \land  x \neq 0 \implies f(x) C(-\infty, 1), C(1,0), C(0, \infty)$$

## Problem 4 

Determine whether $f$ and $g$ are linearly independent on (-1,1)

$f(x),g(x)$ are linearly independent iff $f(x) \neq  cg(x), \forall x,c \in \mathbb{R}, c \neq 0$

$$f(x) = sin^2x + cos^2x$$
$$g(x) = 1$$

If a determinant equal to zero, then there exists some c s.t. $f(x) = cg(x)$

$$W(f,g) = fg' - gf'$$

$$f(x) = sin^2x + cos^2x$$
$$f'(x) = 2sinxcosx - 2cosxsinx $$
$$g(x) = 1$$
$$g'(x) = 0$$


$$W(f,g) = 0 - 0 = 0$$
$$\therefore \exists ~c \ni f(x) = cg(x)$$
