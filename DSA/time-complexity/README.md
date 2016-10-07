## Introduction to time complexity

### Analyze Loops  

<br/>
  
**1. Linear Loop :**  
> A loop has linear factor when increment or decrement consists of addition or subtraction of constant c.

<br/>

#### Addition :

```Java
for(int i=0;i<n;i=i+1)
	c = a + b;

```
<br/>

#### Subtraction :

```Java
for(int i=0;i<n;i=i-1)
	c = a + b;

```

<br/>

Thus the execution is linearly dependent on the value of **n**.
```
T(n) = n
```
<br/>  

| n     | No. of times C is executed |
|-------|----------------------------|
| 10    | 10                         |
| 100   | 100                        |
| 1000  | 1000                       |
| 10000 | 10000                      |
