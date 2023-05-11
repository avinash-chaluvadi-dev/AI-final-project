# Hi, I'm Smoke Detector! 👋
I am a module known for detecting smoke from past history. What a cool name!🤠

**What is a smoke detector ?:**
`I am a module designed to detect smoke, which is commonly an indication of a fire. These detectors usually have sensors that are triggered when smoke is detected, and an alarm system that alerts people to evacuate. There are different types of smoke detectors, including ionization and photoelectric ones. Recently, advances in technology have led to the development of smoke detectors that use IOT devices and AI models to increase their efficiency and accuracy in detecting fires!🤠`

**How smoke detectors are essential to AI ?:** `Smoke detectors are significant components in AI-based
fire detection systems. These systems use advanced algorithms to analyze data gathered from smoke detectors
and other sensors to identify smoke patterns and locate the source of the fire. The smoke detectors are crucial in
providing important information to these systems, helping them make accurate predictions and take immediate
measures to minimize the risk of fires. As a result, smoke detectors play an essential role in enhancing the
accuracy and reliability of AI-based fire detection system.`

## Detailed workflow

Phase 1: Data Analysis & Preparation

In this phase, the project performs an initial analysis of the dataset and prepares the data for further processing. Key steps include:
<ul>

<li> Importing necessary Python libraries for data analysis and visualization.</li>
<li> Loading the dataset from a CSV file.</li>
<li> Gaining insights into the dataset, such as checking for missing values, understanding
    data statistics, and exploring the distribution of the target variable (stroke).
    Performing data cleaning by removing rows with missing values and visualizing the
    distribution of features using density plots and count plots.</li>
</ul>

Phase 2: Building an Overfitting Model

In this phase, the project builds a neural network model that overfits the entire dataset. This step
aims to understand the model's behavior and evaluate its performance. The steps involved are:

<ul>
<li> Building a sequential neural network model with multiple layers and appropriate activation functions. </li>
<li> Compiling the model with the binary cross-entropy loss function and the Adam optimizer. </li>
<li> Training the model on the entire dataset and monitoring its accuracy over multiple
epochs. </li>
<li> Analyzing the model's accuracy using line plots to identify potential overfitting or
convergence. </li>
</ul>

Phase 3: Model Selection & Evaluation

In this phase, the project focuses on selecting the best model architecture and evaluating its performance using training and validation datasets. The steps involved are:
<ul>
<li>Shuffling the dataset to ensure random distribution of data.</li>
<li>Splitting the dataset into training and validation sets.</li>
<li>Building multiple neural network models with different architectures and activation
functions. </li>
<li>Compiling the models with appropriate loss functions and optimizers. </li>
<li>Training the models on the training dataset while monitoring their accuracy on the
validation dataset. </li>
<li>Evaluating the models' accuracy and selecting the best-performing model based on the
validation accuracy.</li>
<li>Visualizing the accuracy of each model over multiple epochs using line plots.</li>
</ul>

Phase 4: Feature Importance and feature selection

In this phase, the project focuses on calculating the the importance of the input features by iteratively removing them iteratively.
<ul>
<li> To determine the importance of each input feature, a model can be trained by using each feature as input and the output as the target variable. This approach allows for the evaluation of the impact of each feature on the model's output. </li>
<li> Starting with the most unimportant feature, remove one feature at a time (without replacement) and train various models. You can iteratively repeat the process removing more and more unimportant features. </li>
</ul>
</ol>


## How to use me ? 💁

```javascript
1. RUN jupyter lab & RUN smoke_detection.ipynb file
```

## Want to test me ? 🧐

No issues! check me, run the following command. Let me give you some dependency issues

```javascript
jupyter nbconvert --execute smoke_detection.ipynb
```

## Something related to installation 🔨

Dude! Install the dependencies.

```sh
pip install -r requirements.txt
```

## Doubts?? Keep them coming 🎤

**Q1. What kind of framework, language and libraries are used to develop the project?**

**Ans.** As already told,
1. Python
2. Tensorflow
3. Pandas
4. Matplotlib
5. Seaborn
6. Lime and Shap

**Q2. How much is the size of dataset?**

**Ans.** The dataset for smoke detection comprises 44757 positive samples indicating fire alarm and a corresponding
number of negative samples, totaling 17871 samples in the dataset.

**Q3. Are you a robot ?**

**Ans.** I prefer to think of myself as your friend. Who also happens to be artificially intelligent.😃