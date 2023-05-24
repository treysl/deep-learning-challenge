# Deep Learning Challenge

In summary, my analysis using machine learning is focused on developing a binary classifier to predict the success of organizations if they receive funding from Alphabet Soup. By leveraging this tool, Alphabet Soup can optimize its selection process and increase the likelihood of supporting ventures that are likely to succeed.

### Data Processing
**My target variables:** for y, the "IS_SUCCESSFUL" column is my target.

**My feature variables:** for X, the columns outside of "IS_SUCCESSFUL" are my features with the exception of EIN and NAME since they have been dropped for privacy reasons.

**Data suggestions:** I suggest removing the 'SPECIAL_CONSIDERATIONS' column from the input data for future testing due to its limited occurrence. The low frequency of special considerations is unlikely to significantly impact the output, making it a suitable candidate for removal."

<img width="676" alt="Screenshot 2023-05-24 at 12 56 34 PM" src="https://github.com/treysl/deep-learning-challenge/assets/96922295/106add2e-5a78-4064-8814-ca7c938cebfb">

### Compiling, Training, and Evaluating the Model
**Neuron layers and activation function counts:** 
- number_input_features = len( X_train_scaled[0])
- hidden_nodes_layer1=7
- hidden_nodes_layer2=14
- hidden_nodes_layer3=21

**Target model performance**
- I selected the current layer amounts based on the provided specifications. Despite conducting experiments with different hidden layer configurations, I was unable to achieve a minimum accuracy score of 75%. The obtained results fell below expectations, indicating the need for further adjustments to improve the model's performance.

### Results Summary
Overall, my model wasn't hitting the banchmarks I set for it. I could improve and analyze my dataset and consider engineering new features that may provide more predictive power. My domain knowledge and understanding of the problem will guide me in creating meaningful features that capture important patterns in the data.
