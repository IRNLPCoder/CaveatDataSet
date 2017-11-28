# CaveatDataSet

## To Do or Not To Do: Distill Crowdsourced Negative Caveats to Augment API Documentation

### 1. "Mentions" fold consists of the sentences which mention the evaluated Java API types.
For example,

|PostId|TypeId|IsBest|Score|API|Sentences|
|--- | --- | --- |--- | --- | --- |
|334145|2|0|6|java.awt.event.ActionListener|You may just want to implement ActionListener in the class where the button and text field resides, so you don't need to declare the two objects as final.|

Number 334145 can track the post on Stack Overflow, i.e., https://stackoverflow.com/questions/334145.

Number 2 indicates that the post is an answer (1 for question).

Number 0 indicates that the answer is not the best answer in the thread. 

Number 6 indicates the answer scores. 

java.awt.event.ActionListener is the mentioned API. 

"You may just want to implement ActionListener in the class where the button and text field resides, so you don't need to declare the two objects as final." is the mentioned sentence.





### 2. "CandidateSentences" fold consists of all candidate sentences in our experiments. 

For example, 

|PostId|TypeId|IsBest|Score|API|Sentences|
|--- | --- | --- |--- | --- | --- |
|5839908|2|0|4|java.awt.event.ActionListener|Note: An ActionListener can't be added to a JPanel, as a JPanel itself does not lend itself to create what is considered to be "actions".|
