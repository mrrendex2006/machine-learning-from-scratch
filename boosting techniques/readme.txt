Boosting is anesemble learning technique that improves predictive accuracy by combining  multiple weak learner into a single strong model.
it works iteratively where each new model focuses on correcting the mistakes of it predeceddors and gradually improves overall performance.
            * Trains  models sequentially , with each learner improveing upon the error of the previous one 
            * Assign higher importance to hard to classify data points, ensuring difficult cases get more focus .
            * combines multiple weak learner using weight aggregation to form a highly accurate strong model .

#HOW BOOSTING WORKS ?
The process focuses on sequentially reducing error by emphasising data points that are harder to classify . By iteratively refining predictions,
boosting improves overall model accuracy .

1. Initialize weights 
All training instances are initially assigned equal weights to represect their importance. these weights determine how much influence each data 
point has on the first weak learner.

2. sequential training 
        * Train the first weak learner on the weighted dataset.
        * Evaluate its predictions and identify misclassified instances.
        * increase the weight of misclassified examples so that the next learner focuses more on these harder cases.

3. Iterative refinement 
This process is repeated for multiple rounds. Each new weak learners is trained on the updated weighted data, addressing the mistake of the existing 
ensemble   gradually improves its  predictive performance.

4. Aggregate predictions 
The outputs of all weak learners are combined to produce the final prediction. Aggregation is typically done using weighted voting or averaging where 
models with higher accuracy have more influence on the final decision .

TYPE OF BOOSTING ALGORITHUM 
Boosting methods differ in how they handel error and combine weak learner to create a strong predictive model.

1.AdaBoost(Adaptive boosting ): assigns higher weights to misclassified data points after each iteration, forcing subsequent learner to focus on harder cases.
It is particularly effective for binary classification problems.

2.Gradient boosting: gradient boosting trains each new model on the residual errors of the previous ensemble, using gradient descent to minimize the loss 
function . it can be applied to both regression and classification tasks . 

