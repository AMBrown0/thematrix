---
share: true
---
### 3.1 Conditional Probability

It is defined as the: Probability of an event A given B equals the probability of B and A happening together divided by the probability of B.”

For example: Assume two partially intersecting sets A and B as shown below.

Set A represents one set of events and Set B represents another. We wish to calculate the probability of A given B has already happened. Lets represent the happening of event B by shading it with red.

![conditional probability](https://www.analyticsvidhya.com/wp-content/uploads/2016/06/1-1.jpg)

Now since B has happened, the part which now matters for A is the part shaded in blue which is interestingly![CodeCogsEqn](https://www.analyticsvidhya.com/wp-content/uploads/2016/06/CodeCogsEqn-1.gif). So, the probability of A given B turns out to be:

![conditional probability](https://latex.codecogs.com/gif.latex?%5Cfrac%7BBlue%20Area%7D%7BRed%20Area+Blue%20Area%7D)

Therefore, we can write the formula for event B given A has already occurred by:

![](https://latex.codecogs.com/gif.latex?P%28B%7CA%29%3D%5Cfrac%7BP%28A%5Ccap%20B%29%7D%7BP%28A%29%7D)

or  
![conditional probability](https://latex.codecogs.com/gif.latex?P%28A%7CB%29%3D%5Cfrac%7BP%28A%5Ccap%20B%29%7D%7BP%28B%29%7D)

Now, the second equation can be rewritten as :

![conditional probability](https://latex.codecogs.com/gif.latex?P%28A%7CB%29%3D%5Cfrac%7BP%28B%7CA%29XP%28A%29%7D%7BP%28B%29%7D)

This is known as **Conditional Probability**.

Let’s try to answer a betting problem with this technique.

Suppose, B be the _event of winning of James Hunt_. A be the _event of raining_. Therefore,

1.  P(A) =1/2, since it rained twice out of four days.
2.  P(B) is 1/4, since James won only one race out of four.
3.  P(A|B)=1, since it rained every time when James won.

Substituting the values in the conditional probability formula, we get the probability to be around 50%, which is almost the double of 25% when rain was not taken into account (Solve it at your end).

This further strengthened our belief  of  James winning in the light of new _evidence_ i.e rain. You must be wondering that this formula bears close resemblance to something you might have heard a lot about. Think!

Probably, you guessed it right. It looks like **Bayes Theorem**.

Bayes  theorem is built on top of conditional probability and lies in the heart of Bayesian Inference. Let’s understand it in detail now.


$$P(A|B)=\frac{P(B|A)\times P(A)}{P(B)}   $$
But
$$P(B|A)=\frac{P(A|B)\times P(B)}{P(A)}$$

Therefore,
$$P(B|A)= \frac{1 \times \frac{1}{4}}{\frac{1}{2}}$$

$$=\frac{1}{2} = 0.5 = 50\% $$
