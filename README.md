# Yelp Sentiment Analysis


Question:<br>
Can we build a neural network using Yelp reviews to accurately classify customer sentiment as positive or negative?

Techniques:<br>
A recurrent neural network (RNN) was used since RNNs can understand text, while convolutional neural networks (CNNs) cannot. The network was built using the Keras library in TensorFlow.


Findings:<br>
The neural network built in this analysis classifies customer sentiment with 79% accuracy using Yelp reviews. The construction of the model involved a process of adjusting and improving the network architecture. Increasing the number of layers and reducing the number of nodes per layer from their original points improved the model's performance.   


Recommendations:<br>
1. This analysis recommends use of the model to continuously monitor customer sentiment. Sentiment prediction from text allows for faster and more convenient data collection processes since customers would not necessarily need to leave a numeric rating attached to their written feedback.
2. Consider promoting incentives enticing customers to express their sentiment on the food and service after their experience at the restaurant. Restaurant practices associated with highly positive sentiments should be reinforced, and those associated with highly negative sentiments should be improved.
3. Consider exploring the opportunity and feasibility of obtaining additional data from social media and other online outlets to monitor social sentiment more broadly. This would result in access to a more robust dataset, representing the customer base more fully, and potentially lead to more substantiated and accurate insights regarding customer sentiment.

