![image](/fig4.png)


We propose Sparse Imitation Reinforcement Learning (SIRL), a hybrid end-to-end control strategy that combines the sparse expert knowledge with reinforcement learning policy for the CARLA autonomous driving task. The sparse expert knowledge provides experience for critical scenarios such as pedestrian and vehicle avoidance and traffic light detection. As we know training RL from scratch is data-inefficient and time consuming and urban driving is probably one of the hardest situations since the state space is large. SIRL provides a solution for these drawback by integrating sparse experience into the driving policy. The experience will guide the RL exploration during the early training stage to accelerate the training process and avoid getting into the catastrophe situation which ensures safe exploration. To some extent, the RL agent is imitating the driving expert's behavior. At the same time, the SIRL agents continuously gains experience therefore it will surpass the sparse expert and pure RL agent individually. We experimentally validate the efficacy of our SIRL agent in complex urban scenario of the CARLA simulator. Besides that, we demonstrate the SIRL agent's generalization ability to mitigate the driving skill to the unseen environment. We additionally show the SIRL's performance for risk-averse exploration and high sample efficiency compared with traditional RL approach.



## SIRL Agent

<p align="center">
<iframe width="280" height="157" src="https://www.youtube.com/embed/eDBZkuJtrNg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>




```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).


