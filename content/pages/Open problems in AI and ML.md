---
category: Resource
tags:
- Reinforcement Learning
title: Open problems in AI and ML
categories: Resource
date: 2024-03-01
lastMod: 2024-03-01
---
[A blog contains 29 Open problems in AI and ML.](https://omnivore.app/shrimansoft/unsolved-problems-in-ai-ai-forum-18df9724871)



## Explainability


## Learning to learn #Evolvebility


  + *Learning to learn* or *meta-learning *(e.g., Harlow, 1949; [Schmidhuber, 1987](http://people.idsia.ch/~juergen/diploma.html); Thrun and Pratt, 1998; [Andrychowicz et al., 2016](https://arxiv.org/abs/1606.04474); [Chen et al., 2016](https://arxiv.org/abs/1611.03824); [de Freitas, 2016](https://www.youtube.com/watch?v=x1kf4Zojtb0); [Duan et al., 2016](https://arxiv.org/abs/1611.02779); [Lake et al., 2016](https://arxiv.org/abs/1604.00289); [Wang et al., 2016](https://arxiv.org/abs/1611.05763)) is the acquisition of skills and inductive biases that facilitate future learning. The scenarios considered in particular are ones where a more general and slower learning process produces a faster, more specialized one. An example is biological evolution producing efficient learners such as human beings.

  + ### Tests

    + Learning to play Atari video games is an area that has seen some remarkable recent successes, including in transfer learning ([Parisotto et al., 2016](https://arxiv.org/abs/1511.06342)). However, there is so far no system that first learns to play video games, then is capable of learning a new game, as humans can, from a few minutes of play ([Lake et al., 2016](https://arxiv.org/abs/1604.00289)).

## Knowing when you don’t know


  + While uncertainty is modeled differently by different learning algorithms, it seems to be true in general that current artificial systems are not nearly as good as humans at “knowing when they don’t know.” An example are deep neural networks that achieve state-of-the-art accuracy on image recognition but assign 99.99% confidence to the presence of objects in images completely unrecognizable to humans ([Nguyen et al., 2015](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Nguyen_Deep_Neural_Networks_2015_CVPR_paper.pdf)).

Human performance on confidence estimation would include

  + In induction tasks, like program induction or sequence completion, knowing when the provided examples are insufficient for induction (multiple reasonable hypotheses could account for them)

  + In speech recognition, knowing when an utterance has not been interpreted reliably

  + In visual tasks such as pedestrian detection, knowing when a part of the image has not been analyzed reliably

  + ### Tests

    + A speech recognizer can be compared against a human baseline, measuring the ratio of the average confidence to the confidence on examples where recognition fails.

    + The confidence of image recognition systems can be tested on generated adversarial examples.

  + 

## Learning through action


  + Human infants are known to learn about the world through experiments, observing the effects of their own actions ([Smith and Gasser, 2005](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.470.5304&rep=rep1&type=pdf); [Malik, 2015](https://www.youtube.com/watch?v=QaF2kkez5XU)). This seems to apply both to higher-level cognition and perception. Animal experiments have confirmed that the ability to initiate movement is crucial to perceptual development ([Held and Hein, 1963](http://www.miamikillianhs.com/ourpages/auto/2011/9/28/55941483/AICS%20Psychol%20%20Held_%20Movement-Produced%20StimulationHeld-1963.pdf)) and some recent progress has been made on using motion in learning visual perception ([Agrawal et al., 2015](http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Agrawal_Learning_to_See_ICCV_2015_paper.pdf)). In ([Agrawal et al., 2016](https://arxiv.org/abs/1606.07419)), a robot learns to predict the effects of a poking action.

“Learning through action” thus encompasses several areas, including

  + Active learning, where the agent selects the training examples most likely to be instructive

  + Undertaking epistemological actions, i.e., activities aimed primarily at gathering information

  + Learning to perceive through action

  + Learning about causal relationships through action

{{< logseq/mark >}}Perhaps most importantly, for artificial systems, learning the causal structure of the world through experimentation is still an open problem.{{< / logseq/mark >}}

  + ### Tests

    + For learning through action, it is natural to consider problems of motor manipulation where in addition to the immediate effects of the agent’s actions, secondary effects must be considered as well.

    + Learning to play billiards: An agent with little prior knowledge and no fixed training data is allowed to explore a real or virtual billiard table and should learn to play billiards well.

## [Transfer flexibility]({{< ref "/pages/Transfer flexibility" >}})


