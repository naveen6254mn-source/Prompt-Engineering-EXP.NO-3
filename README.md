EX.NO:3 Exploring the different types of prompts- Straightforward Prompts - Tabular Format Prompting - Missing Word Prompting - Preceding Question Prompting.

Aim: To write the prompts for the following prompt types for 2 different scenarios of Each type.

1.Straightforward Prompts

2.Tabular Format Prompting

3.Preceding Question Prompting

4.Missing Word Prompting

Explanation - Any one use case from Unit 5 or any 2 own use cases with the unit 2 Prompt type

Procedure:

Write 2 different prompts for different use cases, refer the following Examples

Example:

Straightforward Prompts:

• "Define photosynthesis in one sentence."

"List three advantages of electric vehicles."

Tabular Format Prompting:

• "Compare and contrast AC and DC current in a table."

• "Provide a table listing five programming languages, their paradigms, and one use case each."

Preceding Question Prompting:

• "Why is climate change a global concern? Explain how greenhouse gases contribute to global warming."

• "How do vaccines work? Describe the process of immunization in simple terms."

Missing Word Prompting:

• "The capital of France is ____."

• "In photosynthesis, plants absorb sunlight to produce ____."

OUTPUT:
Exploring the different types of prompts- Straightforward Prompts - Tabular Format Prompting - Missing Word Prompting - Preceding Question Prompting.

1.Straightforward Prompts:

Example 1:“Explain supervised versus unsupervised learning.”
Output:
Supervised Learning vs Unsupervised Learning
Machine learning can be broadly divided into supervised learning and unsupervised learning, based on how the data is used during training.
________________________________________
1. Supervised Learning
Definition:
Supervised learning is a type of machine learning where the model is trained using labeled data. This means each training example has an input and a known output (target). The algorithm learns the relationship between them so it can predict outputs for new data.
Key Characteristics
	Uses labeled datasets
	The model learns from input–output pairs
	Goal is to predict correct outputs for new inputs
Common Tasks
	Classification: Predicting categories (e.g., spam or not spam)
	Regression: Predicting continuous values (e.g., house price)
Examples
	Email spam detection
	Image recognition
	Weather prediction
	Predicting exam scores
Popular Algorithms
	Linear Regression
	Logistic Regression
	Decision Trees
	Support Vector Machines (SVM)
	Neural Networks
________________________________________
2. Unsupervised Learning
Definition:
Unsupervised learning is a type of machine learning where the algorithm works with unlabeled data. The system tries to find hidden patterns, structures, or relationships in the data without predefined outputs.
Key Characteristics
	Uses unlabeled datasets
	No predefined correct answers
	Focuses on discovering patterns or grouping data
Common Tasks
	Clustering: Grouping similar data points together
	Association: Finding relationships between variables
	Dimensionality Reduction: Reducing the number of variables while preserving information
Examples
	Customer segmentation in marketing
	Market basket analysis
	Grouping similar news articles
	Detecting unusual patterns in data
Popular Algorithms
	K-Means Clustering
	Hierarchical Clustering
	Apriori Algorithm
	Principal Component Analysis (PCA)
________________________________________
3. Key Differences Between Supervised and Unsupervised Learning
Feature	Supervised Learning	Unsupervised Learning
Data Type	Labeled data	Unlabeled data
Goal	Predict outputs	Discover patterns
Human Guidance	Required	Not required
Common Tasks	Classification, Regression	Clustering, Association
Example	Spam detection	Customer segmentation
________________________________________
4. Conclusion
In summary, supervised learning uses labeled data to make predictions, while unsupervised learning analyzes unlabeled data to uncover hidden patterns. Both approaches are essential in machine learning and are used in various real-world applications such as recommendation systems, fraud detection, and data analysis.

Example 2:“ How do neural networks work?”

Output:
Neural Networks: How They Work
A neural network is a machine learning model inspired by the structure of the human brain. It consists of interconnected nodes called neurons that process data and learn patterns to make predictions or decisions.
________________________________________
1. Structure of a Neural Network
A neural network is typically organized into three main layers:
1. Input Layer
	The input layer receives the raw data.
	Each neuron represents one feature of the data.
	Example: In an image recognition system, inputs may be pixel values.
2. Hidden Layers
	These layers perform computations and pattern recognition.
	Each neuron receives inputs, multiplies them by weights, adds a bias, and applies an activation function.
	Deep neural networks contain multiple hidden layers.
3. Output Layer
	Produces the final result or prediction.
	Example outputs:
	Class label (cat/dog)
	Numerical value (house price)
________________________________________
2. Basic Working Process
Step 1: Input Data
Data is fed into the network through the input layer.
Step 2: Weighted Sum Calculation
Each neuron calculates a weighted sum:
z=∑(w_i x_i)+b

Where:
	x_i= input values
	w_i= weights
	b= bias
Step 3: Activation Function
The neuron passes the result through an activation function to introduce non-linearity.
Common activation functions include:
	ReLU (Rectified Linear Unit)
	Sigmoid
	Tanh
	Softmax
Step 4: Forward Propagation
The processed data moves layer by layer from input to output, producing a prediction.
________________________________________
3. Learning Process (Training)
Neural networks learn by adjusting weights through a process called training.
Loss Function
The network compares its prediction with the correct answer and calculates the error (loss).
Backpropagation
The error is propagated backward through the network to update the weights.
Weight Update
Using an optimization algorithm (such as Gradient Descent), weights are adjusted to reduce the error.
________________________________________
4. Simple Example
Consider a neural network used for handwritten digit recognition:
	Input layer receives pixel values of the image.
	Hidden layers detect edges, shapes, and patterns.
	Output layer predicts which digit (0–9) the image represents.
________________________________________
5. Applications of Neural Networks
Neural networks are widely used in many fields, including:
	Image and face recognition
	Speech recognition
	Natural language processing
	Medical diagnosis
	Autonomous vehicles
	Recommendation systems
________________________________________
6. Conclusion
Neural networks work by passing data through layers of interconnected neurons that learn patterns using weights, biases, and activation functions. Through repeated training and error correction, the network improves its ability to make accurate predictions or classifications.

2.Tabular Format Prompting:

Example 1:“ You are a data science professor. Explain the fundamentals of machine learning, its types, and real-world applications for beginners. Present the answer with clear headings and examples.In Tabular format”

Output:
Module 1: Core Fundamentals
Before diving into types, we must understand the "Big Picture" of how ML differs from traditional programming.
Concept	Traditional Programming	Machine Learning
Input	Data + Explicit Rules	Data + Answers (Labels)
Process	Computer follows a recipe	Computer finds the recipe (patterns)
Output	A specific result	A predictive model
________________________________________
Module 2: The Three Primary Types of Learning
We categorize ML based on how the "student" (the algorithm) receives information.
Learning Type	How it Works	Analogy	Real-World Example
Supervised	Learning with a labeled dataset (Teacher gives answers).	Flashcards with a word on one side and a picture on the other.	Email Spam Filter: Sorting mail into "Spam" or "Inboxed".
Unsupervised	Finding hidden structures in unlabeled data (No teacher).	Sorting a bucket of mixed LEGOs by color without being told the colors.	Customer Segmentation: Grouping shoppers by spending habits.
Reinforcement	Learning through rewards and penalties (Trial and error).	Training a dog with treats for sitting and "no" for jumping.	Self-Driving Cars: Learning to stay in lanes to avoid "penalties" (crashes).
________________________________________
Module 3: Key Machine Learning Tasks
In the field, we usually solve one of these three specific problems.
Task	Type	Goal	Example
Regression	Supervised	Predict a continuous numerical value.	Predicting a house price based on square footage.
Classification	Supervised	Assign data into specific categories.	Predicting if a tumor is "Malignant" or "Benign".
Clustering	Unsupervised	Group similar items together.	Organizing news articles by "Sports," "Politics," or "Tech."
________________________________________
Module 4: Everyday Applications
You likely interact with these "professors" of data every single day without realizing it.
Application	ML Type Used	How it helps you
Netflix/YouTube	Unsupervised / Filtering	Recommends videos based on what similar users watched.
FaceID / Photos	Supervised (Classification)	Recognizes your unique facial features to unlock your phone.
Google Maps	Regression / Predictive	Analyzes traffic data to predict your "Estimated Time of Arrival."
ChatGPT / AI	Deep Learning (Advanced)	Predicts the next most logical word in a sentence based on context.


Example 2: "You are an AI researcher. Compare supervised, unsupervised, and reinforcement learning. Present the explanation in a structured table with definitions, examples, and advantages."

Output:
Gemini said
As an AI researcher, I look at these three paradigms as the primary ways we "program" intelligence. The choice between them depends entirely on the availability of data and the specific goal of the system.
Here is the structural comparison of the three pillars of machine learning.
Comparative Analysis of Learning Paradigms
Feature	Supervised Learning	Unsupervised Learning	Reinforcement Learning
Definition	The model learns from a labeled dataset, mapping inputs to known correct outputs.	The model identifies hidden patterns or structures within unlabeled data.	The model learns through interaction, receiving rewards or penalties for its actions.
Core Goal	To predict or classify new, unseen data accurately.	To discover underlying clusters or compress data features.	To learn a sequence of decisions that maximizes a reward.
Analogy	A student learning from a textbook with an answer key at the back.	A child sorting a box of mixed toys into groups without being told the categories.	A person learning to ride a bicycle by balancing and adjusting after a fall.
Common Examples	Email spam detection, house price prediction, medical diagnosis.	Customer market segmentation, anomaly detection, topic modeling.	Game-playing AI (AlphaGo), robotics, autonomous vehicle navigation.
Advantages	High Precision: Very accurate for specific, defined tasks. Simple Evaluation: Easy to measure performance against known labels.	Discovery: Finds patterns humans might miss. Data Efficient: Does not require expensive manual labeling of data.	Autonomy: Can learn complex tasks without a "correct" example. Adaptability: Improves over time in changing environments.



3.Preceding Question Prompting:

Example 1:
What is machine learning?
What are the main types of machine learning?
Using the answers to the above questions, explain machine learning and its types with suitable real-world examples for beginners.

Output:
1. What is Machine Learning?
In simple terms, Machine Learning is a branch of Artificial Intelligence (AI) that allows a computer to learn from experience (data) without being explicitly programmed for a specific task.
Think of it like teaching a child to recognize a "chair." You don't give them a geometric blueprint; you show them various chairs until their brain recognizes the pattern. In ML, we show the computer thousands of examples, and it builds a mathematical model to recognize those patterns.
________________________________________
2. The Three Main Types of Machine Learning
Type	How it Works	Real-World Example
Supervised Learning	Learning with a "Teacher." You give the model labeled data (input + correct answer).	Spam Filters: You mark emails as "Spam," and the model learns to catch similar ones.
Unsupervised Learning	Learning by "Discovery." The model looks at unlabeled data and finds hidden patterns.	Netflix Suggestions: It groups users with similar tastes without being told what the "genres" are.
Reinforcement Learning	Learning by "Trial and Error." The model interacts with an environment and gets rewards or penalties.	Chess AI: It plays millions of games against itself, learning that winning earns a "reward."
________________________________________
3. Explaining ML to a Beginner (With Examples)
To understand how these work in your daily life, imagine you are building a "Smart Assistant" for a fruit shop.
Supervised Learning: The "Scanner"
You want a camera to identify if a fruit is an Apple or an Orange.
	The Process: You show the computer 500 photos of apples labeled "Apple" and 500 oranges labeled "Orange."
	The Result: When a customer holds up a new fruit, the computer compares its features (color, texture) to its training and says, "That is an Apple."
Unsupervised Learning: The "Customer Specialist"
You have a list of 1,000 customers but don't know who they are.
	The Process: You feed their buying history into the model. It notices that one group buys only organic kale, while another group buys only chocolate.
	The Result: It creates "Clusters." You didn't tell it these groups existed; it discovered them based on the data.
Reinforcement Learning: The "Delivery Robot"
You have a small robot that delivers fruit to houses.
	The Process: The robot tries different paths. If it hits a wall, it gets a "penalty" (negative score). If it reaches the door quickly, it gets a "reward" (positive score).
	The Result: Over thousands of trips, the robot learns the most efficient path through the neighborhood.

Example 2:
What are the common algorithms used in machine learning?
How does training data affect machine learning models?
Based on the above questions, write a short explanation of how machine learning models are built and trained in real-world applications.

Output:
1. Common Machine Learning Algorithms
Algorithms are the mathematical engines that power the model. The choice depends on the problem you are trying to solve.
Category	Common Algorithms	Best Used For...
Regression	Linear Regression, Lasso	Predicting prices, temperatures, or stocks.
Classification	Random Forest, SVM, Logistic Regression	Identifying spam, disease diagnosis, or fraud.
Clustering	K-Means, DBSCAN	Grouping similar customers or news topics.
Deep Learning	CNN (Neural Networks), RNN	Image recognition and language translation.
________________________________________
2. The Impact of Training Data
Training data is the "experience" the model learns from. The old saying in data science is "Garbage In, Garbage Out."
	Quantity: Models generally perform better with more data, as they can see more variations of a pattern.
	Quality: If data is biased or contains errors, the model will learn those mistakes. For example, if a "Pass/Fail" model only sees data from one specific school, it might fail to predict results for students elsewhere.
	Relevance: The data must represent the real-world scenario the model will actually face.
________________________________________
3. How Models are Built in the Real World
In professional applications, building a model is a cyclical process rather than a straight line.
Step 1: Data Preparation
Engineers collect and "clean" raw data. This involves removing duplicates, fixing missing values, and scaling numbers so the algorithm can process them easily.
Step 2: Selection and Training
An algorithm (like a Random Forest) is chosen. The data is split: roughly 80% goes to Training (to teach the model) and 20% goes to Testing (to see if it actually learned).
Step 3: Evaluation and Tuning
The model is tested on the 20% "hidden" data. If the accuracy is low, engineers "tune" the model—adjusting its internal settings (hyperparameters) to get better results.
Step 4: Deployment and Monitoring
Once accurate, the model is put into a real app (like the Netflix recommendation engine). It is monitored constantly to ensure that as the world changes, the model stays relevant.

4.Missing Word Prompting:
Example 1: Machine learning is a subset of ______ that enables computers to learn from data without being explicitly programmed.

Output:
Machine learning is a subset of Artificial Intelligence (AI) that enables computers to learn from data without being explicitly programmed.

Example 2: In machine learning, a model improves its performance by learning patterns from ______ during the training process.

Output:
In machine learning, a model improves its performance by learning patterns from data during the training process.





RESULT: 
