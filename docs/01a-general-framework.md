# Framework

A framework is used so that we can have consistent pattern across the company, else every engineer would do what ever they want.

## Parts/ stages in ML project

- **Data Collection**: *in this phase we try to answer this question*
  - what data exists?
  - where and how you will get this data from?
  - is the data structured or unstructured?
- **Data modelling**:
  - **problem definition**: what problem we are trying to solve? *is it a supervised, or unsupervised? is it classification or regression problem?*
  - **Data**: What kind of data do we have? *is the data in excel? is it structured or unstructured?, is the data text or audio or images?*
  - **Evaluation**: What defines success? *expected output, this is crucial as ML is experimental in nature, we can go forever trying to find a solution. Hence success criteria is important. There is not perfect ML model for a solution do not exits*
  - **Features**: what do we already know about the data? what features/attribute/characteristics should we model? *for example to predict durability of car, body-type may be a feature we want to model on, but not the color of a car(even though this data is available)*
  - **Modelling**: What kind of model should we use? *based on data and problem statement, what Ml model should we use?(node in ML models are already coded and available, we need to write model for very unique problem)*
  - **Experiment**: what have we tried, what else can we try? *may be new training data, or new features*
- **Deployment**:
  - use the ML model and deploy it, so that it can be used/accessed through your application or API.

## Example: