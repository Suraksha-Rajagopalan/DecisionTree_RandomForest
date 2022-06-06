# 🌳DecisionTree🌲🌳🌲🌳🌲RandomForest

<h2> 🌳🌱🍄Classification</h2>
<p> Classification is the problem of identifying which of a set of categories (sub-populations) an observation (or observations) belongs to. In machine 
  learning classification is an algorithm that uses one or more independent variables to determine an outcome. A commonn example of classification, 
  can be the differentiation of dog and cat.</p>
  <img alt="animals" scr="https://imgs.search.brave.com/IAZHjV_evwrVtFbHMO4hMTf75n7CcxKVw8E0e2RA-9k/rs:fit:844:225:1/g:ce/aHR0cHM6Ly90c2Uy/Lm1tLmJpbmcubmV0/L3RoP2lkPU9JUC5J/Z1VHdEl1UVBmYklB/V1lSQmtIal9BSGFF/SyZwaWQ9QXBp">
  
  <h2> 🌳Decision Tree</h2>
  <p>The decision tree algorithm builds the classification model in the form of a tree structure. It utilizes the if-then rules which are equally 
  exhaustive and mutually exclusive in classification. The process goes on with breaking down the data into smaller structures and eventually associating it 
  with an incremental decision tree. The learning process is continuous and based on feedback. This improves the outcome of learning over time. This kind 
  of learning is called supervised learning. Therefore, decision tree models are support tools for supervised learning. A decision tree starts from the 
  root or the top decision node that classifies data sets based on the values of carefully selected attributes.The algorithm used by decision tree is called <b>cart</b>.</p>
  
  <p>The <b>root node</b> represents the entire dataset. This is where the first step in the algorithm selects the best predictor variable. It makes it a 
  <b>decision node</b>. It also classifies the whole dataset into various classes or smaller datasets. The set of criteria for selecting attributes is 
  called <b>Attribute Selection Measures (ASM)</b>. ASM is based on selection measures, including information gain, entropy, Gini index, Gain ratio, and so on. 
  These attributes, also called features, create decision rules that help in <b>branching</b>. The branching process splits the root node into sub-nodes, splitting 
  further into more sub-nodes until leaf nodes are formed. Leaf nodes cannot be divided further.</p>
  
  <p><b>Gini Index</b>:Also known as Gini impurity, calculates the amount of probability of a specific feature that is classified incorrectly when selected 
  randomly. If all the elements are linked with a single class then it can be called pure. Gini index varies between values 0 and 1.</p>
  
  <p><b>Entropy</b>:The measure of disorder, or measure of purity. Basically, it is the measurement of the impurity or randomness in the data points.</p>
  
  <p><b>Information Gain</b>:Information Gain is applied to quantify which feature provides maximal information about the classification based on the 
  notion of entropy, i.e. by quantifying the size of uncertainty, disorder or impurity, in general, with the intention of decreasing the amount of entropy 
  initiating from the top (root node) to bottom(leaves nodes).</p>
  
  <h3> 👍Advantages </h3>
  <p>1.Requires less effort when compared to other algorithms</p>
  <p>2.It does not require normalization of data</p>
  <p>3.Does not require scaling of data</p>
  <p>4.The missing values of data doesn't effect the building of the decision tree</p>
  <p>5.The model is very intuitive and easy to explain </p>
  
  <h3> 👎Disadvantages </h3>
  <p>1.A small change in the data can cause a large change in the structure of the decision tree causing instability.</p>
  <p>2.For a Decision tree sometimes calculation can go far more complex compared to other algorithms.</p>
  <p>3.Decision tree often involves higher time to train the model.</p>
  <p>4.Decision tree training is relatively expensive as the complexity and time has taken are more.</p>
  <p>5.The Decision Tree algorithm is inadequate for applying regression and predicting continuous values.</p>
  
  
  <h2> 🌲🌳🌲🌳🌲Random Forest</h2>
<p>Random forest is a flexible, easy-to-use machine learning algorithm that produces, even without hyper-parameter tuning, a great result most of the time. It is also one of the most-used algorithms, due to its simplicity and diversity (it can be used for both classification and regression tasks). The "forest" it builds is an ensemble of decision trees, usually trained with the “bagging” method. The general idea of the bagging method is that a combination of learning models increases the overall result.</p>
 
 <p>Random forest adds additional randomness to the model, while growing the trees. Instead of searching for the most important feature while splitting a node, it searches for the best feature among a random subset of features. This results in a wide diversity that generally results in a better model. Therefore, in random forest, only a random subset of the features is taken into consideration by the algorithm for splitting a node. You can even make trees more random by additionally using random thresholds for each feature rather than searching for the best possible thresholds (like a normal decision tree does).</p>
 
 <p>Random forest algorithm is that it is very easy to measure the relative importance of each feature on the prediction. Sklearn provides a great tool for this that measures a feature’s importance by looking at how much the tree nodes that use that feature reduce impurity across all trees in the forest. Random forest improves on bagging because it decorrelates the trees with the introduction of splitting on a random subset of features. This means that at each split of the tree, the model considers only a small subset of features rather than all of the features of the model. That is, from the set of available features n, a subset of m features (m=square root of n) are selected at random. This is important so that variance can be averaged away. Consider what would happen if the data set contains a few strong predictors. These predictors will consistently be chosen at the top level of the trees, so we will have very similar structured trees. In other words, the trees would be highly correlated.</p>
 
 <h3> 👍Advantages of Random Forest</h3>
 <p>1.Parallelizable</p>
 <p>2.Great with High dimensionality</p>
 <p>3.Quick Prediction/Training Speed</p>
 <p>4.Robust to Outliers and Non-linear Data</p>
 <p>5.Handles Unbalanced Data</p>
 <p>6.Low Bias, Moderate Variance</p>
 
 <h3> 👎Disadvantage</h3>
 <p>1.Model interpretability: Random forest models are not all that interpretable; they are like black boxes.</p>
 <p>2.For very large data sets, the size of the trees can take up a lot of memory.</p>
 <p>3.It can tend to overfit, so you should tune the hyperparameters.</p>
 
  
  
