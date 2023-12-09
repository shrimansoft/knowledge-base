---
type:
- blog
title: Why Neural network
tags:
categories:
date: 2023-12-08
lastMod: 2023-12-09
---
Hello, everyone. I recently gave a talk on neural networks at the NISER Coding Club. The address was intended for a general audience. So, we have yet to use any technical jargon.
In this post, I will convey the same here, But before I begin I like to point out that this bog has some exercise that is degined to make you absrobe the matarial for its fullest. So, if you are reading to Get the Real

We begin with the definition of the RuLU function.

## ReLU

  + $$\sigma(x) = \max(0,x)$$

![image.png](/assets/image_1701949023644_0.png)

  + 

  + ### Examples of ReLU

    + Let's see some of the examples variation of this function ReLU. To get the deeper undrrstading of this I like you to pratice this simple exercise.

    + 
$$\sigma(x+1)$$

![image.png](/assets/image_1701949545078_0.png)

    + 
$$\sigma(x-1)$$

![image.png](/assets/image_1701949568750_0.png)

    + 
$$\sigma(x-1) +1$$

![image.png](/assets/image_1701949589726_0.png)

    + 
$$\sigma(-x)$$

![image.png](/assets/image_1701949673223_0.png)

    + $$\sigma(-x-1)$$

![image.png](/assets/image_1702131097800_0.png)

      + 

  + ### Some More Examples

    + $$\sigma(x)- \sigma(x-1)$$

![image.png](/assets/image_1702131123809_0.png)

    + $$\sigma(x-0) -\sigma(x-1) + \sigma(x-2) - \sigma(x-3)$$

![image.png](/assets/image_1702131227572_0.png)

    + $$\sigma(x-0) -\sigma(x-1) + \sigma(x-2) - \sigma(x-3) -\sigma(x-4) +\sigma(x-6)$$

![image.png](/assets/image_1702131355502_0.png)

  + ### Some Exercise

    + These Exercise will me the above Idea concrete in your mind and you will have no problem understanding the next part of the blog.

    + 1. Plot the graph of the following function

      + $$-\sigma(x-1)$$

    + 2. Plot the graph of the following function

      + $$\sigma(x-2)$$

    + 3. Plot the graph of the following function

      + $$-\sigma(x-3)$$

    + 4. If you can plot the above try poling the combination of above two:

      + $$\sigma(x-2) -\sigma(x-3)$$

  + Very good.

## Neural network.

  + https://upload.wikimedia.org/wikipedia/commons/thumb/4/46/Colored_neural_network.svg/500px-Colored_neural_network.svg.png

  + The above picture I took from the Wikipedia [page](https://en.wikipedia.org/wiki/Artificial_neural_network). If you see here you will get lot of thing about it's aplication, model user and a lot, but Right now we will look at a perticuler exmaple of it and see what its all about. Lets begin.

![image.png](/assets/image_1702133212150_0.png)

  + This is how a simple nuron looks, if we write it matamaticaly its a function $y:\mathbb{R}\to\mathbb{R}$.

  + $$y(x) = \sigma(Wx + B)$$

  + where $\sigma$ is ReLU function that we looked at the above.

  + So $\sigma(x) will look like:

![image.png](/assets/image_1702133440403_0.png)

  + Very good. its plot will be same as $\sigma(x)$.

  + ### Examples

    + Now we will repeat the above example and see how thy look as neural network.

    + 
$$\sigma(x+1)$$

![image.png](/assets/image_1702133666312_0.png)

![image.png](/assets/image_1701949545078_0.png)

    + 

    + 
$$\sigma(x-1)$$

![image.png](/assets/image_1702133688094_0.png)

![image.png](/assets/image_1701949568750_0.png)

    + 
$$\sigma(x-1) +1$$

![image.png](/assets/image_1702133879603_0.png)

![image.png](/assets/image_1701949589726_0.png)

    + 
$$\sigma(-x)$$

![image.png](/assets/image_1701949673223_0.png)

    + $$\sigma(-x-1)$$

![image.png](/assets/image_1702131097800_0.png)

      + 

  + ### Some More Examples

    + $$\sigma(x)- \sigma(x-1)$$

![image.png](/assets/image_1702131123809_0.png)

    + $$\sigma(x-0) -\sigma(x-1) + \sigma(x-2) - \sigma(x-3)$$

![image.png](/assets/image_1702131227572_0.png)

    + $$\sigma(x-0) -\sigma(x-1) + \sigma(x-2) - \sigma(x-3) -\sigma(x-4) +\sigma(x-6)$$

![image.png](/assets/image_1702131355502_0.png)

  + ### Some Exercise

    + These Exercise will me the above Idea concrete in your mind and you will have no problem understanding the next part of the blog.

    + 1. Plot the graph of the following function

      + $$-\sigma(x-1)$$

    + 2. Plot the graph of the following function

      + $$\sigma(x-2)$$

    + 3. Plot the graph of the following function

      + $$-\sigma(x-3)$$

    + 4. If you can plot the above try poling the combination of above two:

      + $$\sigma(x-2) -\sigma(x-3)$$

  + Very good.


