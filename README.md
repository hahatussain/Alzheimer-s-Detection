# Background
Dementia manifests as a set of related symptoms, which usually surface when the brain is damaged by injury or disease.[4] The symptoms involve progressive impairments to memory, thinking, and behavior, which negatively impact a person's ability to function and carry out everyday activities. Aside from memory impairment and a disruption in thought patterns, the most common symptoms include emotional problems, difficulties with language, and decreased motivation.

# CDT Test
The Clock Drawing Test (CDT) is a simple test to detect signs of dementia. In this test the patient is asked to draw an analog clock with hands on the clock indicating ‘ten minutes past 11 o’clock.’ This single test may be sensitive to dementia because it involves many cognitive areas that can be affected by dementia, including executive function, visuospatial abilities, motor programming, attention, and concentration. A qualified doctor then examines the drawing for the signs of dementia.

![Superior-pattern-processing-is-the-essence-of-the-evolved-human-brain-fnins-08-00265-g0004](https://user-images.githubusercontent.com/53375807/123837826-ec38d980-d928-11eb-8b00-2762586ba4b9.jpg)

# Problem Statement
The challenge is to use the features extracted from the Clock Drawing Test to build an automated algorithm to predict whether each participant is in one of three phases:

1)    Pre-Alzheimer’s (Early Warning)
2)    Post-Alzheimer’s (Detection)
3)    Normal (Not an Alzheimer’s patient)

# Solution
### Approach
Catboost(A gradient boosted decision tree algorithm) was used to classify the data points in the given dataset into the required 3 categories

### What are Gradient Boosted Decision Trees?
Gradient boosting is a machine learning technique for regression, classification and other tasks, which produces a prediction model in the form of an ensemble of weak prediction models, typically decision trees. When a decision tree is the weak learner, the resulting algorithm is called gradient boosted trees, which usually outperforms random forest. It builds the model in a stage-wise fashion like other boosting methods do, and it generalizes them by allowing optimization of an arbitrary differentiable loss function.
