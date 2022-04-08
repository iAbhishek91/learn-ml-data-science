# Problem Definition

**problem definition**: what problem we are trying to solve? *is it a supervised, or unsupervised? is it classification or regression problem?*

## Step-1a: is ML appropriate for your problem**

There are scenario when we should not use ML -- when a simple hand-coded instruction based system work, do NOT try to complicate things using ML.

## Step-1b: match your scenario/problem with main types of ML

- **Supervised learning**:
  - you have data(inputs) and label[known output]
  - the models try to use the data to predict the label
  - If the answer is wrong we tell this to the program that its wrong, and repeats the process.
  - Problem we solve:
    - **classification**:
      - classify the data is this or that? *a flower is rose or not? have kidney problem or not?*
      - *types*: binary classification(*find kidney problem or not*), multi-class classification (*find dog breeds*)
    - **regression**:
      - trying to predict a number
      - *examples*: *how much will this house sell for?, how many people will buy this app*

- **Unsupervised learning**:
  - you have data(inputs) but no labels(definite output)
  - you need to define/derive most common labels
  - problem we solve:
    - **clustering**: group data and put label based on any common attribute like month range. *example: who can be our target audience for marketing this summer*
    - **association rule learning**:
    - **regression**

- **Transfer learning**: you apply basic foundation of existing ML model and try to a implement that in to another model. Basically leveraging the basic of existing model to build another model. *for example: how to write a good essay Ml model, can be used to model how to write a good poem(instead of writing from scratch)*

- **Reinforcement learning**(not so common): teaching machine through trial and errors, initially it will not know what to be done. but in each iteration it will try to figure out what is the best. In this type we respond with *award/right/positive* or *punish/wrong/negative* the machine *problem we solve: skill acquisition, real time learning*. *example: training Ml model to make it learn chess(award with win or loose every time.)*

The goal is common from the data we are trying to figure out something (a goal).
