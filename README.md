# MIT FutureMakers
Deep learning and AI Summer Program
## Responses
- [X] July 6: What do I hope to learn from this summer?
  - Familiarity with machine learning concepts and syntax in order to become comfortable with AI overall
- [X] July 7: What did I learn from the leadership seminar?
  - The power of stories come from small details that allow the reader to become invested into the moment and the larger theme
- [X] July 8: What is the difference between supervised and unsupervised learning? Can Scikit-Learn visualize data without a data analysis library?
  - In supervised learning we know what the outputs should be, allowing the program to learn by comparing its output to the expected output. Unsupervised learning on the other hand has no known or "labeled" outputs, so it learns by finding patterns and clustering similar groups of things together. 
  - No, although Scikit-Learn is an easy to use machine learning library, it does not have built-in data analysis, so it must be imported from an external library.
- [X] July 9: What real world problem can be solved using machine learning and a relevant data set?
  - https://www.kaggle.com/sansuthi/world-population-by-year
  - Calculating world population data is vital to determining future sources of conflict in our world, and through detailed population statistics in data sets such as the one above, we can make accurate predictions based on regression analysis.
- [X] July 12: What are Tensors? How did the computations work on the Tensorflow tutorial?
  - Tensors are arrays of some unspecifed dimension. First order tensors being vectors, as they occur in only one dimension, and second order tensors being matrices, as they occur in two dimensions. 
  - The program makes guesses using the 784 inputs of each image, pixels, and produces one of 62 outputs, the different types of signs. The guesses are really just mathmatically equations from differing weights of the values of the inputs. Those weights are then changed, as the programs improves its ability to give out accurate sign predictions, or outputs.
- [X] July 15: How were machine learning concepts used in the "Survival of the Best Fit" game? What is a real world example of bias in a machine learning model, and what would be a solution to improve it?
  - In the game, a machine learning algorithm was created by mimicing real world decisions based on real world data. This ended up promulgating baises inherent to real world data.  
  - In 2018, Amazon shut down an AI algorithm intended to help automate hiring. As it turned out, the algorithm was heavily skewed towards hiring men due to its training model, Amazon's historical hiring data, exhibiting the same bias. The model had begun to assign significant influence to data that should have been irrelevant and not included in the information fed to the program, such as specific verb usage in resumes. In a model that creates outputs through a largely unknown system, it is the duty of the programmer to eliminate bias from the data as much as possible, and then consistently monitor the program to make sure that it doesn't diverge from its intended process.
