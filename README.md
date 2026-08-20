## Tekmir Data Science Intern Challenge
#### Author: Nicole Huynh; nthuynhbc@gmail.com

### Track 1: Fictional Domain Packet
In this mock scenario, I have been given a dataset from SignalDesk. I picked the suggested question: "Which workflow seems most useful right now?" This entire notebook and mini-writeup took me about 1h20m to complete. The writing and programming is my own.

The trickiest part of this question was figuring out which variables would be useful here -- ultimately, I decided to primarily examine the percentage of user-accepted outputs out of all outputs completed by the model, across all three teams: **Sales**, **Product**, and **Support**. Intuitively, the workflow with both the highest percentage of user-accepted outputs and lowest percentage of user-flagged outputs would be the most helpful in a workplace environment, as helping to successfully complete mundane tasks is a hallmark of a useful product. To confirm which workflow functioned best, I also compared the percentage of user-accepted outputs with the model's median confidence (both proxies for human/AI's definition of "correctness").

Given more time with this scenario, I would perform a more robust analysis and use the average time saved per task to further support my conclusion. This dataset is also very, very small, and I might use bootstrapping to conduct my analysis again to make sure my conclusion is reliable and consistent.