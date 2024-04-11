
## Module 21 - Alphabet Soup Application Analysis

* Purpose: The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. Using knowledge of machine learning and neural networks, use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

* The model was trained to predict application success.


## Results: Using bulleted lists and images to support your answers, address the following questions:

* Data Preprocessing
    * What variable(s) are the target(s) for your model?
        IS_SUCCESSFUL

    * What variable(s) are the features for your model?
        APPLICATION_TYPE
        AFFILIATION
        CLASSIFICATION
        USE_CASE
        ORGANIZATION
        INCOME_AMT
        
    * What variable(s) should be removed from the input data because they are neither targets nor features?
        EIN
        NAME

* Compiling, Training, and Evaluating the Model

    * How many neurons, layers, and activation functions did you select for your neural network model, and why?
        I tried different sets of numbers as the hidden nodes in the layers, but I did it based on the example code.  It is unclear to me how these numbers affect the models.
        I also tried adjusting the binning ranges, but that also did not make much of a difference.
    *  Were you able to achieve the target model performance?
        No
    *  What steps did you take in your attempts to increase model performance?
        I tried adjusting the number of neurons but nothing I changed seemed to have much impact.

* Summary:


