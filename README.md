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
  
  
  
