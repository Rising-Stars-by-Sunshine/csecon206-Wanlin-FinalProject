# # New Love Game Model: A Dynamic Analysis of Nash Equilibirum
## Project information
- **Author**: Wanlin Deng, Political Economy, Class of 2025, Duke Kunshan University
- **Instructor**: Prof. Luyao Zhang, Duke Kunshan University
- **Disclaimer**: Submissions to Final Project for [COMPSCI/ECON 206 Computational Microeconomics, 2023 Spring (Seven Week - Second)](https://ce.pubpub.org/) instructed by Prof. Luyao Zhang at Duke Kunshan University.
- **Acknowledgments**: I want to thank Professor Luyao Zhang for her inspiring ideas for classifying game players according to their values and designing the payoff matrix accordingly. Thanks Rong Cong for providing peer evaluation that improves my project a lot. And thanks to everyone in the class for the inspiring discussion.
- **Project Summary**: 
  - [Summarize the Background/Motivation] <br>
  
    In the past, John Nash simplified the love game to a binary choice between "Date" and "Not to Date," proposing that the Nash equilibrium occurred when both players chose "Not to Date." However, this oversimplified model lacks meaningful insights into real-world romantic dynamics. In real life, people do not always make straightforward decisions about whether to date or not. Instead, they often choose to keep things ambiguous, maintaining a level of intimacy that goes beyond friendship but falls short of being in a relationship. Since Nash equilibrium represents a state that no one has anything to gain by changing only one's own strategy, and in reality, people are indeed striving for this kind of optimal state, why does Nash equilibrium fail to predict people's inclinations accurately? This question has inspired the project. <br>
    
  - [Research Questions] <br>
  How to predict the choices people with different personalities make when facing potential dating partners in real life using game theory? <br>
  
  - [Application Scenario] <br>
  The newly proposed love game model here applies to all real-world love game analyses. However, with the core idea of varying the payoff matrix accordingly, this project applies to all real-world scenarios where different people have varied degrees of utility for the same outcome according to their different values and beliefs.<br>
  
  - [Methodology]<br>
  In this project, I modify the original love game model by adding a third strategy, "keep courting," for each person. Then, I design three game scenarios, which are the players perfectly meet each other's ideal standards, the players partially meet each other's ideal standards and both are altruistic, the players partially meet each other's ideal standards and both are egoistic. The payoff matrix will vary in different scenarios. Finally, I will solve their Nash equilibrium solution and check how players' preferred outcomes vary.<br>
  
  - [Results] <br>
  When players perfectly meet each other's mate selection criteria, their preferred outcomes are "Date/Date" or "Keep courting/Keep courting." When players only partially meet each other's mate selection criteria, and both players are altruistic, the Nash equilibrium solution suggests that their preferred outcome is either "Date/Date" or "Keep courting/Keep courting." When players only partially meet each other's mate selection criteria, and both players are selfish, the Nash equilibrium solution suggests that their preferred outcome is "Date/Date" or "Not to Date/Not to Date." Interestingly, the results show that regardless of the scenario or player type involved, one of the ideal outcomes of the game is always "Date/ Date." These simulation results are much closer to real life and better able to predict human behavior than the original binary love game.<br>
  - [Intellectual Merits and Practical impacts of your project.] <br>
  One major criticism of Nash equilibrium is its strong assumption that all players are rational. It is widely recognized that players are not always rational due to personal preferences and values. However, this project proposes allowing for dynamic changes in the matrix based on individual players' personal values. By incorporating people's values into the payoff matrix, this project demonstrates how players with different values evaluate their actual payoff in a given strategy profile. In this way, the "rational" assumption of Nash equilibrium becomes more plausible, as people are indeed seeking the best outcome based on their own values. By dynamically altering the payoff matrix, this project greatly expands the scope and accuracy of Nash equilibrium in predicting real-world decision-making. This provides new insights into the real-world application of game theory.
  
   
Note: please insert the screenshot of the answers to your research question by ChatGPT. The methodology that you use to address the research questions must be more innovative than both the current literature and ChatGPT. 
- [Screenshot of ChatGPT.] <br>

## Table of Contents

- The polished version of Problem Sets
- Final poster
- Final project Overleaf
- Final project Google Colab
- More about the author
- References

### The polished version of Problem Sets
In this part, I modify the problem sets and address the comment provided by Prof.Luyao point by point. Here is the details for the modifications:<br>

- Reversion of [problem set 1](https://github.com/Rising-Stars-by-Sunshine/csecon206-Wanlin-PS1.git):<br>

1.	Correct the misunderstanding between strategy and strategy profile.
2.	Include in-text citation and reference whenever introduce terminologies (e.g., for forward induction and Q-learning algorithms).
3.	Provide the definition of efficiency and fairness when evaluating the game.<br>

- Reversion of [problem set 2](https://github.com/Rising-Stars-by-Sunshine/csecon206-Wanlin-PS2.git):<br>

1.	Clean all the red logs in the overleaf documents.
2.	Provide page numbers when citing the book for definition and theorem.
3.	Embed the complied PDF in the spotlight part for an easy access of my overleaf content.

### Final poster 
<img src="Final poster.png">

### Final project overleaf
- The [overleaf PDF](https://github.com/Rising-Stars-by-Sunshine/csecon206-Wanlin-FinalProject/blob/fac547ebe87ecdd08a9f3e52da4e0151da394514/spotlight/CSECON206_FinalProject_Spring2023_Wanlin.pdf) is uploaded to the spotlight file.
- The [.zip file](https://github.com/Rising-Stars-by-Sunshine/csecon206-Wanlin-FinalProject/blob/d802f923a14627c821f69ade31219c46c2608ba0/code/CSECON206_FinalProject_Spring2023-Wanlin.zip) of overleaf is uploaded in the code file.


### Final project Google Colab
- The [code](https://github.com/Rising-Stars-by-Sunshine/csecon206-Wanlin-FinalProject/blob/fbfe35cc9c25f061ef268986c8d018f484b9fc7c/code/Game_simulation.ipynb) for the final project is uploaded in the code file.


### More about the Author
- Self Intro

<img src="生活照.png" width="100px">

My name is Wanlin Deng, and you can also call me Iris. I’m from the class of 2025 and my major is political Economy with a track in economics. I’m interested in the interdisciplinary field of computational economics. Now, I’m working on utilizing all the math, econ and coding knowledge to study economics in a more critical way, and hope to become a competitive person who possesses a truly interdisciplinary capability. <br>

Nice to meet you guys here and look forward to our future cooperation!

- Final reflections 
  - intellectual growth
  - professional growth<br>
  How do you grow professionally in this course to acquire a combination of skills and create professional profiles? <br>
  
  In this course, two of my most important takeaways were becoming proficient in using GitHub and Overleaf. I learned how to effectively upload code from Google Colab to GitHub and run code from others' repositories in my own Google Colab environment. Additionally, I learned how to use a README file to succinctly and effectively explain the contents in repositories. These skills are crucial for me to share the code of my own research on websites publicly and to utilize and learn from open-source code created by others. Proficiency in GitHub enables me to leverage and contribute to online resources, thus enhancing my professional growth.<br>
  Furthermore, becoming adept at using Overleaf has equipped me with the ability to present my articles in a publishable format. The provided Overleaf templates in the course also taught me how to showcase my personal information in an Overleaf PDF formally. This skill will greatly assist me in creating professional presentations of my working portfolio in the future. 
Overall, these two skills have transformed me from a college student writing papers in Word documents to a potential talent with solid interdisciplinary research skills.

  
  - living a purposeful life

### References

- Literature References in [Chicago Author-Date](https://www.chicagomanualofstyle.org/tools_citationguide/citation-guide-2.html) Style and [BibTex](https://scholar.google.com/) 

Levin, Dan, and Luyao Zhang. 2020. “Bridging Level-K to Nash Equilibrium.” *The Review of Economics and Statistics* 104 (6): 1329–40. https://doi.org/10.1162/rest_a_00990.

```
@article{levin2022bridging,
  title={Bridging level-k to nash equilibrium},
  author={Levin, Dan and Zhang, Luyao},
  journal={Review of Economics and Statistics},
  volume={104},
  number={6},
  pages={1329--1340},
  year={2022},
  publisher={MIT Press One Rogers Street, Cambridge, MA 02142-1209, USA journals-info~…}
}
```

