# Vocab auto correction system

![Auto correct](images/auto-correct.png "Auto correct")

You use autocorrect every day on your cell phone and computer. In this project, you will explore what really goes on behind the scenes. Of course, the model you are about to see is not identical to the one used in your phone, but it is still quite good. 

By completing this project you will learn how to: 

- Get a word count given a corpus
- Get a word probability in the corpus 
- Manipulate strings 
- Filter strings 
- Implement Minimum edit distance to compare strings and to help find the optimal path for the edits. 
- Understand how dynamic programming works


Similar systems are used everywhere. 
- For example, if you type in the word **"I am lerningg"**, chances are very high that you meant to write **"learning"**, as shown in **Figure 1**. 

# Contents
0. Overview
    - Edit Distance
1. Data Preprocessing
    - process data
    - get count
    - get probs
2. String Manipulation
    - delete letter
    - switch letter
    - replace letter
    - insert letter
3. Combining the edits
    - edit one letter
    - edit two letters
    - get corrections
4. Minimum Edit Distance
    - min edit_distance

# Credits

- NLP specialization by Deeplearning.ai on coursera
