# Machine_Learning_Challenge
Exo-planet raw data analysis with machine learning neural networks model. If in need to see just 1 file, review the LAST (Model 1_copy4) and read this README to understand the actual assignment process.

My work on this hoework consisted on 4 models thar reflect my learning process on this particular topic:
Model 1 file is the first raw attempts; using a set of 15 columns as X and doing the process (split data, pre-process, train, test, etc). Results were loss: 0.2507 - acc: 0.9113. However this file has an issue in the Grid Search that later on was fixed since the full approach / my understanding was incorrect

Model 1_copy2 is the same thinking process as the previous' file but adding more columns of the dataset, the test model yielded better results: Test Neural Network - Loss: 0.0709433174208318, Accuracy: 0.9816933870315552; but same mistake on the Grid Search approach was present

Model 1_copy3; after some coaching and research I was able to identify the mistake on the Gridsearch which was applying a diferent paramter search than the one that actually requires a neural networks which is Epochs and batch size. With this in mind this latter part of the code was updated to perform the right search in the same way the previous' file was done. Results with 15 inputs were: 
      RESULTS COMPARISSON:
      First trained/test deep_model: Accuracy= 0.914  Loss = 0.246
      Same deep_model/data with With tuned parameters: Accuracy = 0.9548 Loss = 0.1566
      
Model 1_copy4. Corrected Grid search approach using 35 inputs and far less epochs (20 vs 50 in the previous run) were:
      RESULTS COMPARISSON:
      First trained/test deep_model: Accuracy= 0.914  Loss = 0.246
      Same deep_model/data with With tuned parameters: Accuracy = 0.988 Loss = 0.0598
 
As it can be seen, the optimization in conjuction with the extended inputs, yield the best accuracy while minimizing the loss of the model with more than 50% epochs reduction ~ faster and more accurate output
