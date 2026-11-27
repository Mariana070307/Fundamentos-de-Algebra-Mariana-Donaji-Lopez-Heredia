# Fundamentos de Álgebra

## Actividad #32 - Gauss y Gauss-Jordan.

### Alumna: Mariana Donaji López Heredia
---
#### Resuelve las ecuaciones por Gauss.

 
## 37)
 
$$
\begin{cases}
6x + y - z = -22 \\
-x + 3y + 3z = 22 \\
-6x - 6z = 12
\end{cases}
$$
 
$$
\left[\begin{array}{ccc|c}
6 & 1 & -1 & -22 \\
-1 & 3 & 3 & 22 \\
-6 & 0 & -6 & 12
\end{array}\right]
\xrightarrow{F_3 \to -\frac{1}{6}F_3}
\left[\begin{array}{ccc|c}
6 & 1 & -1 & -22 \\
-1 & 3 & 3 & 22 \\
1 & 0 & 1 & -2
\end{array}\right]
\xrightarrow{F_1 \leftrightarrow F_3}
\left[\begin{array}{ccc|c}
1 & 0 & 1 & -2 \\
-1 & 3 & 3 & 22 \\
6 & 1 & -1 & -22
\end{array}\right]
$$
 
$$
\xrightarrow{\substack{F_2 \to F_2 + F_1 \\ F_3 \to F_3 - 6F_1}}
\left[\begin{array}{ccc|c}
1 & 0 & 1 & -2 \\
0 & 3 & 4 & 20 \\
0 & 1 & -7 & -10
\end{array}\right]
\xrightarrow{F_2 \leftrightarrow F_3}
\left[\begin{array}{ccc|c}
1 & 0 & 1 & -2 \\
0 & 1 & -7 & -10 \\
0 & 3 & 4 & 20
\end{array}\right]
$$
 
$$
\xrightarrow{F_3 \to F_3 - 3F_2}
\left[\begin{array}{ccc|c}
1 & 0 & 1 & -2 \\
0 & 1 & -7 & -10 \\
0 & 0 & 25 & 50
\end{array}\right]
$$

**Solución:** $x = -4,\; y = 4,\; z = 2$

## 38)
 
$$
\begin{cases}
-4a - 3b - 2c = -8 \\
a - 4b - 2c = -3 \\
4a - 2b + c = 6
\end{cases}
$$
 
$$
\left[\begin{array}{ccc|c}
-4 & -3 & -2 & -8 \\
1 & -4 & -2 & -3 \\
4 & -2 & 1 & 6
\end{array}\right]
\xrightarrow{F_1 \leftrightarrow F_2}
\left[\begin{array}{ccc|c}
1 & -4 & -2 & -3 \\
-4 & -3 & -2 & -8 \\
4 & -2 & 1 & 6
\end{array}\right]
$$
 
$$
\xrightarrow{\substack{F_2 \to F_2 + 4F_1 \\ F_3 \to F_3 - 4F_1}}
\left[\begin{array}{ccc|c}
1 & -4 & -2 & -3 \\
0 & -19 & -10 & -20 \\
0 & 14 & 9 & 18
\end{array}\right]
\xrightarrow{F_2 \to F_2 + F_3}
\left[\begin{array}{ccc|c}
1 & -4 & -2 & -3 \\
0 & -5 & -1 & -2 \\
0 & 14 & 9 & 18
\end{array}\right]
$$
 
$$
\xrightarrow{F_3 \to 5F_3 + 14F_2}
\left[\begin{array}{ccc|c}
1 & -4 & -2 & -3 \\
0 & -5 & -1 & -2 \\
0 & 0 & 31 & 62
\end{array}\right]
$$

**Solución:** $a = 1,\; b = 0,\; c = 2$

## 39)
 
$$
\begin{cases}
a + 5b - 4c = -14 \\
2a - 5b - 5c = -7 \\
3a + 3b + 2c = -2
\end{cases}
$$
 
$$
\left[\begin{array}{ccc|c}
1 & 5 & -4 & -14 \\
2 & -5 & -5 & -7 \\
3 & 3 & 2 & -2
\end{array}\right]
\xrightarrow{\substack{F_2 \to F_2 - 2F_1 \\ F_3 \to F_3 - 3F_1}}
\left[\begin{array}{ccc|c}
1 & 5 & -4 & -14 \\
0 & -15 & 3 & 21 \\
0 & -12 & 14 & 40
\end{array}\right]
$$
 
$$
\xrightarrow{\substack{F_2 \to -\frac{1}{3}F_2 \\ F_3 \to \frac{1}{2}F_3}}
\left[\begin{array}{ccc|c}
1 & 5 & -4 & -14 \\
0 & 5 & -1 & -7 \\
0 & -6 & 7 & 20
\end{array}\right]
\xrightarrow{F_3 \to 5F_3 + 6F_2}
\left[\begin{array}{ccc|c}
1 & 5 & -4 & -14 \\
0 & 5 & -1 & -7 \\
0 & 0 & 29 & 58
\end{array}\right]
$$

**Solución:** $a = -1,\; b = -1,\; c = 2$

## 40)
 
$$
\begin{cases}
6x + 6y + 5z = 16 \\
-6x + 6y + z = 20 \\
2x - 2y + 3z = 0
\end{cases}
$$
 
$$
\left[\begin{array}{ccc|c}
6 & 6 & 5 & 16 \\
-6 & 6 & 1 & 20 \\
2 & -2 & 3 & 0
\end{array}\right]
\xrightarrow{\substack{F_2 \to F_2 + F_1 \\ F_3 \to 3F_3 - F_1}}
\left[\begin{array}{ccc|c}
6 & 6 & 5 & 16 \\
0 & 12 & 6 & 36 \\
0 & -12 & 4 & -16
\end{array}\right]
$$
 
$$
\xrightarrow{F_3 \to F_3 + F_2}
\left[\begin{array}{ccc|c}
6 & 6 & 5 & 16 \\
0 & 12 & 6 & 36 \\
0 & 0 & 10 & 20
\end{array}\right]
$$

**Solución:** $x = -1,\; y = 2,\; z = 2$
  
## 41)
 
$$
\begin{cases}
-2a + b - 4c = 7 \\
4a + 6b + c = 19 \\
-6a - 6b - 5c = -17
\end{cases}
$$
 
$$
\left[\begin{array}{ccc|c}
-2 & 1 & -4 & 7 \\
4 & 6 & 1 & 19 \\
-6 & -6 & -5 & -17
\end{array}\right]
\xrightarrow{\substack{F_2 \to F_2 + 2F_1 \\ F_3 \to F_3 - 3F_1}}
\left[\begin{array}{ccc|c}
-2 & 1 & -4 & 7 \\
0 & 8 & -7 & 33 \\
0 & -9 & 7 & -38
\end{array}\right]
$$
 
$$
\xrightarrow{F_3 \to F_3 + F_2}
\left[\begin{array}{ccc|c}
-2 & 1 & -4 & 7 \\
0 & 8 & -7 & 33 \\
0 & -1 & 0 & -5
\end{array}\right]
\xrightarrow{F_2 \leftrightarrow F_3}
\left[\begin{array}{ccc|c}
-2 & 1 & -4 & 7 \\
0 & -1 & 0 & -5 \\
0 & 8 & -7 & 33
\end{array}\right]
$$
 
$$
\xrightarrow{F_3 \to F_3 + 8F_2}
\left[\begin{array}{ccc|c}
-2 & 1 & -4 & 7 \\
0 & -1 & 0 & -5 \\
0 & 0 & -7 & -7
\end{array}\right]
$$

**Solución:** $a = -3,\; b = 5,\; c = 1$

## 42)
 
$$
\begin{cases}
5a - 3b + 5c = 22 \\
-4a - b + c = -16 \\
2a + 4b - c = 11
\end{cases}
$$
 
$$
\left[\begin{array}{ccc|c}
5 & -3 & 5 & 22 \\
-4 & -1 & 1 & -16 \\
2 & 4 & -1 & 11
\end{array}\right]
\xrightarrow{F_1 \leftrightarrow F_3}
\left[\begin{array}{ccc|c}
2 & 4 & -1 & 11 \\
-4 & -1 & 1 & -16 \\
5 & -3 & 5 & 22
\end{array}\right]
$$
 
$$
\xrightarrow{\substack{F_2 \to F_2 + 2F_1 \\ F_3 \to 2F_3 - 5F_1}}
\left[\begin{array}{ccc|c}
2 & 4 & -1 & 11 \\
0 & 7 & -1 & 6 \\
0 & -26 & 15 & -11
\end{array}\right]
\xrightarrow{F_3 \to 7F_3 + 26F_2}
\left[\begin{array}{ccc|c}
2 & 4 & -1 & 11 \\
0 & 7 & -1 & 6 \\
0 & 0 & 79 & 79
\end{array}\right]
$$
 
**Solución:** $a = 4,\; b = 1,\; c = 1$
 
## 43)
 
$$
\begin{cases}
-3a + 5b = 26 \\
-6a + 4b + c = 26 \\
3a + 5b + 3c = 8
\end{cases}
$$
 
$$
\left[\begin{array}{ccc|c}
-3 & 5 & 0 & 26 \\
-6 & 4 & 1 & 26 \\
3 & 5 & 3 & 8
\end{array}\right]
\xrightarrow{\substack{F_2 \to F_2 - 2F_1 \\ F_3 \to F_3 + F_1}}
\left[\begin{array}{ccc|c}
-3 & 5 & 0 & 26 \\
0 & -6 & 1 & -26 \\
0 & 10 & 3 & 34
\end{array}\right]
$$
 
$$
\xrightarrow{F_3 \to 3F_3 + 5F_2}
\left[\begin{array}{ccc|c}
-3 & 5 & 0 & 26 \\
0 & -6 & 1 & -26 \\
0 & 0 & 14 & -28
\end{array}\right]
$$
 
**Solución:** $a = -2,\; b = 4,\; c = -2$
 
## 44)
 
$$
\begin{cases}
5a - 5b - c = -30 \\
5a - 6b - c = -29 \\
-5a + 4b - 4c = 6
\end{cases}
$$
 
$$
\left[\begin{array}{ccc|c}
5 & -5 & -1 & -30 \\
5 & -6 & -1 & -29 \\
-5 & 4 & -4 & 6
\end{array}\right]
\xrightarrow{\substack{F_2 \to F_2 - F_1 \\ F_3 \to F_3 + F_1}}
\left[\begin{array}{ccc|c}
5 & -5 & -1 & -30 \\
0 & -1 & 0 & 1 \\
0 & -1 & -5 & -24
\end{array}\right]
$$
 
$$
\xrightarrow{F_3 \to F_3 - F_2}
\left[\begin{array}{ccc|c}
5 & -5 & -1 & -30 \\
0 & -1 & 0 & 1 \\
0 & 0 & -5 & -25
\end{array}\right]
$$
 
**Solución:** $a = -6,\; b = -1,\; c = 5$
 
####  
## 45) Variables: $r, s, t$
 
$$
\left[\begin{array}{ccc|c}
4 & -5 & -1 & -20 \\
-1 & 2 & 1 & -1 \\
-1 & 1 & 0 & -4
\end{array}\right]
\xrightarrow{(1)}
\left[\begin{array}{ccc|c}
1 & -1 & 0 & 4 \\
0 & 1 & 1 & 3 \\
0 & 0 & 0 & -33
\end{array}\right]
$$
 
**(1)** $F_3 \to -F_3$, $F_1 \leftrightarrow F_3$, $F_2 \to F_2 + F_1$, $F_3 \to F_3 - 4F_1$, $F_3 \to F_3 + F_2$
 
 La última fila al ser $0 = -33$; se  considera como un sistema sin solución. 
 
## 46) Variables: $a, b, c$
 
$$
\left[\begin{array}{ccc|c}
-5 & -5 & 5 & 10 \\
-6 & 0 & -2 & -16 \\
-6 & 0 & 1 & -19
\end{array}\right]
\xrightarrow{(1)}
\left[\begin{array}{ccc|c}
1 & 1 & -1 & -2 \\
0 & -3 & 4 & 14 \\
0 & 0 & 3 & -3
\end{array}\right]
\xrightarrow{(2)}
\left[\begin{array}{ccc|c}
1 & 0 & 0 & 3 \\
0 & 1 & 0 & -6 \\
0 & 0 & 1 & -1
\end{array}\right]
$$
 
**(1)** $F_1 \to -\frac{1}{5}F_1$, $F_2 \to -\frac{1}{2}F_2$, $F_2 \to F_2 - 3F_1$, $F_3 \to F_3 + 6F_1$, $F_3 \to F_3 + 2F_2$
 
**(2)** $F_3 \to \frac{1}{3}F_3$, $F_1 \to F_1 + F_3$, $F_2 \to F_2 - 4F_3$, $F_2 \to -\frac{1}{3}F_2$, $F_1 \to F_1 - F_2$
 
**Solución:** $a = 3,\; b = -6,\; c = -1$

## 47) Variables: $a, b, c$
 
$$
\left[\begin{array}{ccc|c}
0 & -3 & -2 & -26 \\
1 & 0 & 2 & 1 \\
2 & -3 & 2 & 3
\end{array}\right]
\xrightarrow{(1)}
\left[\begin{array}{ccc|c}
1 & 0 & 2 & 1 \\
0 & -3 & -2 & -26 \\
0 & 0 & 0 & 27
\end{array}\right]
$$
 
**(1)** $F_1 \leftrightarrow F_2$, $F_3 \to F_3 - 2F_1$, $F_3 \to F_3 - F_2$
 
La última fila al ser $0 = 27$; se  considera como un sistema sin solución. 

## 48) Variables: $r, s, t$
 
$$
\left[\begin{array}{ccc|c}
3 & 0 & -1 & 8 \\
-2 & 1 & 0 & -5 \\
-3 & -3 & 5 & -1
\end{array}\right]
\xrightarrow{(1)}
\left[\begin{array}{ccc|c}
1 & 1 & -1 & 3 \\
0 & 3 & -2 & 1 \\
0 & 0 & 2 & 8
\end{array}\right]
\xrightarrow{(2)}
\left[\begin{array}{ccc|c}
1 & 0 & 0 & 4 \\
0 & 1 & 0 & 3 \\
0 & 0 & 1 & 4
\end{array}\right]
$$
 
**(1)** $F_1 \to F_1 + F_2$, $F_2 \to F_2 + 2F_1$, $F_3 \to F_3 + 3F_1$
 
**(2)** $F_3 \to \frac{1}{2}F_3$, $F_1 \to F_1 + F_3$, $F_2 \to F_2 + 2F_3$, $F_2 \to \frac{1}{3}F_2$, $F_1 \to F_1 - F_2$
 
**Solución:** $r = 4,\; s = 3,\; t = 4$

## 49) 
 
$$
\left[\begin{array}{ccc|c}
0 & -6 & 3 & 15 \\
-3 & -6 & 0 & -6 \\
1 & -6 & 4 & 22
\end{array}\right]
\xrightarrow{(1)}
\left[\begin{array}{ccc|c}
1 & -6 & 4 & 22 \\
0 & 2 & -1 & -5 \\
0 & 0 & 0 & 0
\end{array}\right]
\xrightarrow{(2)}
\left[\begin{array}{ccc|c}
1 & 0 & 1 & 7 \\
0 & 1 & -\frac{1}{2} & -\frac{5}{2} \\
0 & 0 & 0 & 0
\end{array}\right]
$$
 
**(1)** $F_1 \leftrightarrow F_3$, $F_2 \to F_2 + 3F_1$, $F_3 \to \frac{1}{3}F_3$, $F_2 \to -\frac{1}{12}F_2$, $F_3 \to F_3 + F_2$
 
**(2)** $F_2 \to \frac{1}{2}F_2$, $F_1 \to F_1 + 6F_2$
 
$$
x = 7 - \lambda,\quad y = \frac{\lambda - 5}{2},\quad z = \lambda,\qquad \lambda \in \mathbb{R}
$$
 
## 50) 
 
$$
\left[\begin{array}{ccc|c}
0 & -3 & 0 & 3 \\
2 & -2 & -6 & -6 \\
5 & 1 & 4 & -21
\end{array}\right]
\xrightarrow{(1)}
\left[\begin{array}{ccc|c}
1 & -1 & -3 & -3 \\
0 & 1 & 0 & -1 \\
0 & 0 & 19 & 0
\end{array}\right]
\xrightarrow{(2)}
\left[\begin{array}{ccc|c}
1 & 0 & 0 & -4 \\
0 & 1 & 0 & -1 \\
0 & 0 & 1 & 0
\end{array}\right]
$$
 
**(1)** $F_1 \to -\frac{1}{3}F_1$, $F_1 \leftrightarrow F_2$, $F_1 \to \frac{1}{2}F_1$, $F_3 \to F_3 - 5F_1$, $F_3 \to F_3 - 6F_2$
 
**(2)** $F_3 \to \frac{1}{19}F_3$, $F_1 \to F_1 + F_2$, $F_1 \to F_1 + 3F_3$
 
**Solución:** $r = -4,\; s = -1,\; t = 0$

## 51) 
 
$$
\left[\begin{array}{ccc|c}
-5 & 0 & 1 & -16 \\
-2 & 2 & 1 & -7 \\
5 & 2 & 4 & 11
\end{array}\right]
\xrightarrow{(1)}
\left[\begin{array}{ccc|c}
1 & 4 & 1 & 2 \\
0 & 2 & 5 & -5 \\
0 & 0 & 22 & -22
\end{array}\right]
\xrightarrow{(2)}
\left[\begin{array}{ccc|c}
1 & 0 & 0 & 3 \\
0 & 1 & 0 & 0 \\
0 & 0 & 1 & -1
\end{array}\right]
$$
 
**(1)** $F_2 \to F_2 - F_1$, $F_3 \to F_3 + F_1$, $F_1 \to F_1 + 2F_2$, $F_2 \to F_2 - 3F_1$, $F_2 \to F_2 + 5F_3$, $F_2 \leftrightarrow F_3$
 
**(2)** $F_3 \to \frac{1}{22}F_3$, $F_1 \to F_1 - F_3$, $F_2 \to F_2 - 5F_3$, $F_2 \to \frac{1}{2}F_2$, $F_1 \to F_1 - 4F_2$
 
**Solución:** $r = 3,\; s = 0,\; t = -1$

## 52) 
 
$$
\left[\begin{array}{ccc|c}
1 & 1 & -5 & 11 \\
-1 & -2 & -3 & 7 \\
6 & -5 & 0 & 28
\end{array}\right]
\xrightarrow{(1)}
\left[\begin{array}{ccc|c}
1 & 1 & -5 & 11 \\
0 & 1 & 8 & -18 \\
0 & 0 & 118 & -236
\end{array}\right]
\xrightarrow{(2)}
\left[\begin{array}{ccc|c}
1 & 0 & 0 & 3 \\
0 & 1 & 0 & -2 \\
0 & 0 & 1 & -2
\end{array}\right]
$$
 
**(1)** $F_2 \to F_2 + F_1$, $F_3 \to F_3 - 6F_1$, $F_2 \to -F_2$, $F_3 \to F_3 + 11F_2$
 
**(2)** $F_3 \to \frac{1}{118}F_3$, $F_1 \to F_1 + 5F_3$, $F_2 \to F_2 - 8F_3$, $F_1 \to F_1 - F_2$
 
**Solución:** $x = 3,\; y = -2,\; z = -2$
