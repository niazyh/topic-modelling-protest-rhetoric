# topic-modelling-protest-rhetoric

**Analysing UK parliamentary debates on protest using structural topic modelling**

This project explored the latent themes that have run through politicians’ speeches about protest in the UK House of Commons from 1972-2022. The transcripts from any debates discussing protest, and from changes to legislation covering protest, were analysed using topic modelling via the stm package in R. Through uncovering the latent patterns and themes in parliamentary discourse, I sought to understand the ways in which politicians have framed protest and police power in the UK to answer the following questions:

1. What latent themes lie underneath politicians’ discussion of political protest in House of Commons debates?

2. How does party affiliation affect politicians’ framing of political protest?

**Key Results**
*See the full paper for more detailed methods and results*

The table below shows the chosen topic labels, along with sections of the debates found to be most strongly associated with that topic. This gives an idea of the kind of speeches that were generating the latent patterns.

![Screenshot 2025-05-29 at 18 04 06](https://github.com/user-attachments/assets/d3fc1eee-13f9-451e-abc3-fdfa78098e50)

Political party was brought in as a covariate, showing which party tended to speak about each topic most frequently. 

![Screenshot 2025-05-29 at 18 08 47](https://github.com/user-attachments/assets/d0cdd341-7b1d-4939-bfa5-f6d7961b6283)

I looked at the language each party used most often when talking about each topic. The visual below shows words commonly used by each party when discussing the theme 'freedom to protest'. Conservatives are more likely to use the word ‘demonstr[ation]’, whereas with Labour the word ‘protest’ is much more strongly associated. Alongside the other frequent words for the Conservative party, ‘weekend’, ‘place’ and ‘parliament’, it seems that speeches associated with this topic are alluding to specific events that have taken place. The words ‘violent’, ‘disrupt’ and ‘public’ also suggest a criminal framing. Labour’s commonly associated words ‘peac[eful]’, ‘right’, ‘freedom’, and ‘democrac[y]’ allude more towards the overarching right to protest, and protest’s place in democracy.

![Screenshot 2025-05-29 at 18 01 14](https://github.com/user-attachments/assets/cee620f9-664e-4da1-9ad8-6579aee4483b)
