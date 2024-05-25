---
title: Diverse perceptron Nerual Network from Tools in RL.
tags:
categories:
date: 2024-05-21
lastMod: 2024-05-21
---
[Diverse perceptron in one Neural Network]({{< ref "/pages/Diverse perceptron in one Neural Network" >}})


> *Question:* How will it do this?
> *Answer:*  I don't know, but this blog gives some insight on this question.

Now we will generalise the idea of using sin(x) in NN {assume that it's possible. We will test whether it is possible with some experiments.}. We can use $e^x$, log(x), and some pertained NN. { this is unusual when you think about that if we replace one of the perceptrons from sin(x).}

But the problem here is how can we just put some function inside a neural network.

Next, **I will deal with this problem by assuming these functions as tools that the neural network learns to use.** These functions say tools are not inside the neural network (Agent). It's just a tool that The Agent use. This will lead us to think about the duality of things that belong to Agents or the World.

I am going to handle the problem using reinforcement learning. Let us state an equivalent problem. The problem is the following. Let us assume we have a machine M that takes the state of chess and return the best next move. Make a world W in which we have this machine $M$ and chessboard C. We have to make an agent that has to learn how to play chess in this world W. This problem is different from than regular chess playing problem because here the optimum strategy is not "learn to play chess" instead "learn to use the machine $M$.”
