

# Module 01: The K-Armed Bandit Problem

## Resources:
- [David Silver's RL Course](https://deepmind.com/learning-resources/-introduction-reinforcement-learning-david-silver)
    - scroll down to Lecture 1
- Reading: Chapter 3.3 (pages 47-56) 

## Lessons - Notes  
### Lesson 1: Markov Decision Processes

- the k-armed bandit problem doesn't account for the fact that different situations call 
for different actions
- account for the long-term impact for our actions
- bandits care only for immediate reward  

- the diagram below summarizes the agent environment interaction in the MDP framework
![](img/module-02/1.JPG)
  
- the agent environment generates a <b>trajectory of experience</b> consisting
of:
  - <i>states</i>
  - <i>actions</i>
  - <i>rewards</i>
  
- actions influence immediate rewards, as well as future states and through these
future rewards
![](img/module-02/2.JPG)
  
\\[ x = {-b \pm \sqrt{b^2-4ac} \over 2a} \\]

$e^{i \pi} = -1$

<script type="text/javascript"
        src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.0/MathJax.js?config=TeX-AMS_CHTML"></script>

