---
alias:
- MDP
icon: 🐾
title: Markove decision process
tags:
categories:
date: 2023-12-02
lastMod: 2024-01-12
---
{{< logseq/orgCENTER >}}RL interaction Dynamics
{{< / logseq/orgCENTER >}}

{{< logseq/orgCENTER >}}RL interaction Dynamics
{{< / logseq/orgCENTER >}}

Markov decision process is a mathematical model.

{{< logseq/orgCENTER >}}![image.png](/assets/image_1679864939461_0.png)
{{< / logseq/orgCENTER >}}

> When we fix the **policy**, the above process becomes automatic. It will just run and run.

Because of a **lack of knowledge**, we use probability in this. #randomness

The above interaction dynamics can be studied using the MDP. So here, the MDP comes into the picture.

The MDP is how the agent sees his interaction with the world.

Let me elaborate on this and show where this idea will fit in the scheme of World view. So, we start our story with two players. One is our robot $R$, and the other one is environment $E$, where the robot $R$ acts on environment $E$.

Let me elaborate on this and show where this idea will fit in the scheme of World view. So, we start our story with two players. One is our robot $R$, and the other one is environment $E$, where the robot $R$ acts on environment $E$.

Now, This is up to how is thinking about all these interactions. Here, the person who is thinking about the interactions. We call it *Thinker* $T$.

Where is this MDP? The MDP is modeled by the *Thinker* $T$, then placed in the code/brain of *robot* $R$.

Now, This is up to how is thinking about all these interactions. Here, the person who is thinking about the interactions. We call it *Thinker* $T$.

Where is this MDP? The MDP is modeled by the *Thinker* $T$, then placed in the code/brain of *robot* $R$.

MDP is representing what? It represents the dynamics of the interaction between *robot* $R$ and the environment $E$.

alring.

alring.

So, What are we getting from this? There are interaction dynamics, which are the partial representation of real interaction dynamics, which happen in the head of the *robot* $R$.

Very good. Now, we can see two interaction flows: one is in the real world, where the actual robot built of motors, battery, and ICS is action on the environment, and the other is in the head of the *robot* $R$.

But the point that concerns me is the model is not built by the *robot* $R$( or some code inside the $R$.) It's something we created and placed in the head of the *robot* $R$.On the other hand, in the case of humans, we found the interaction dynamics on our own.

The above leads me to questions as follows:

So, What are we getting from this? There are interaction dynamics, which are the partial representation of real interaction dynamics, which happen in the head of the *robot* $R$.

Very good. Now, we can see two interaction flows: one is in the real world, where the actual robot built of motors, battery, and ICS is action on the environment, and the other is in the head of the *robot* $R$.

But the point that concerns me is the model is not built by the *robot* $R$( or some code inside the $R$.) It's something we created and placed in the head of the *robot* $R$.On the other hand, in the case of humans, we found the interaction dynamics on our own.

The above leads me to questions as follows:

  + How do we know that we are not part of this environment? How do we know that the table is not the same as the pen, which is above it? How do we know how to interact with them? The tool concept made us aware of how we interact in this world and how an object interacts with other things in the world. 

Remark: In the above line where I write "object" is the world in the World view.

Let me elaborate on this and give a picture of where this idea will fit in the scheme of World view. So, we start our story with two players: one, our robot $R$, and another, the enlivenment where the robot acts.

Let me elaborate on this and give a picture of where this idea will fit in the scheme of World view. So, we start our story with two players: one, our robot $R$, and another, the enlivenment where the robot acts.

By looking at the above situation. I am going to propose an experimental challenge as follows: 
 
**The Challenge**: Given a $agent world$ interaction. where the world is consist of two worlds say $world$ := $world 1$ <-> $world 2$. the challenge the agent has is to find the MDP which represent the $agent$ <-> $world$ to The MDP which is representing the $agent$ <-> $world 1$ <-> $world 2$. 
 
 OK the next problem is how can we write the MDP with three interacting or three world. where each of them.

Triangular MDP

This MPP is the generalisation of the interaction with the world that Is and built. When you think about a bike, you don't see all the nuts and bolts. You see how it operates and how its state changes when you perform some action. the Idea of a bike is the MDP of the Bike in our head. 

This is cool. When I say I know something i.e. I know the behaviour of that thing and how it changes based on my action. I know the dynamic rules of that person or thing. #knowing

**Remark:** Most real scenarios are unlikely to be Markov.

  + **Question:** How are we dealing with this? this question has two parts. one, what are the technic we have in computer science to deal with this. another one is how we humans are dealing with this.

  + **Answer:** I don't this will have a clear and clean answer. but let me mention some points. 
1. **Memory** of the past states that we use to handle this.
2. we can have Indexes That depends on the past state. Through this we can gather some particular information for the past states.
3. There is a quote that I read in the course of Second Brain that "we humans are good at recognising then recalling". So, what this is saying this how we retreat information from our Memory. #Memory

  + 

  + 
