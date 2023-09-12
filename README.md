# week 3
- [Exercise 3.a.3](#exercise-3a3)
    - [Method 1 (Consider two fractions individually first):](#method-1-consider-two-fractions-individually-first)
    - [Method 2 (Combine two fractions first):](#method-2-combine-two-fractions-first)
- [Exercise 8.c](#exercise-8c)
- [Exercise 8.d](#exercise-8d)
- [Exercise 9.b](#exercise-9b)
## Exercise 3.a.3
$$\frac{1}{1+3i}+ \frac{1}{(1+3i)^{2}}$$
### Method 1 (Consider two fractions individually first):
First fraction,
$$\frac{1}{1+3i}$$

$$=\frac{1}{1+3i}\cdot \frac{1-3i}{1-3i}$$

$$= \frac{1-3i}{10}$$
Second fraction,
$$\frac{1}{(1+3i)^{2}}$$

$$= \frac{1}{-8+6i}$$

$$=\frac{1}{-8+6i} \cdot \frac{-8-6i}{-8-6i}$$

$$= \frac{-8-6i}{100}$$
Sum of the two fractions,
$$\frac{1-3i}{10} + \frac{-8-6i}{100}$$

$$= \frac{10-30i-8-6i}{100}$$

$$= \frac{2-36i}{100}$$

$$= \frac{1}{50} - \frac{9i}{25}$$
### Method 2 (Combine two fractions first):
$$\frac{1}{1+3i}+ \frac{1}{(1+3i)^{2}}$$

$$=\frac{1+3i}{(1+3i)^{2}}+\frac{1}{(1+3i)^{2}}$$

$$=\frac{2+3i}{(1+3i)^{2}}$$

$$=\frac{2+3i}{-8+6i}$$

$$=\frac{2+3i}{-8+6i} \cdot \frac{-8-6i}{-8-6i}$$

$$=\frac{2-36i}{100}$$

$$=\frac{1}{50} - \frac{9i}{25}$$
## Exercise 8.c
$$b=5,~c=\frac{6}{7},~d=\frac{2}{3}$$

$$c+d=\frac{6}{7}+ \frac{2}{3}=\frac{18}{21}+ \frac{14}{21}=\frac{32}{21}$$

$$d\cdot b=\frac{2}{3}\cdot 5= \frac{10}{3}$$

$$\frac{b}{d}= \frac{5}{\frac{2}{3}}=5\cdot \frac{3}{2}=\frac{15}{2}$$

$$\frac{d}{c}= \frac{2}{3} \div \frac{6}{7}=\frac{2}{3}\cdot \frac{7}{6}=\frac{7}{9}$$
## Exercise 8.d
$$k=1+\sqrt{3}i,~ n=5i,~ m=1+i,~ s=3+4i$$

$$\frac{m}{n}= \frac{1+i}{5i}=\frac{i-1}{-5}=\frac{1}{5}- \frac{i}{5}$$

$$\frac{k}{s}= \frac{1+\sqrt{3}i}{3+4i}= \frac{3+4\sqrt{3}}{25}+ \frac{3\sqrt{3}-4}{25}i$$

$$\frac{1}{m}+s=\frac{1}{1+i}+3+4i=\frac{1-i}{2}+3+4i=\frac{7}{2}+ \frac{7}{2}i$$
## Exercise 9.b
Let us compare values $i$ and $0$.
According to *the first theorem*, only one of the following statements is true,
$$i=0,~i>0,~i<0$$
- It is clear that the first statement ($i=0$) is false, because in the complex number plane, $i$ and $0$ represents different complex numbers.

- Let us consider the second statement ($i>0$):
Assume $i>0$ is true, then according to *the fourth theorem*, I can apply this,
>If $0 < i$ and $0 < i$, then $0 \cdot i < i \cdot i$.

which give a contradiction, because it gives $0<-1$.

- Let us consider the third statement ($i<0$):
Assume $i<0$ is true, then $-i>0$.
According to *the fourth theorem*, I can apply this,
>If $i < 0$ and $0 < -i$, then $-i \cdot i < -i \cdot 0$.

which give a contradiction, because it gives $1<0$.

In conclusion, none of the statements in *the first theorem* is true, and therefore the order relation **cannot** be extended to apply all complex numbers.
