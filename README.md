# Arabic_handwritten_characters_recognetion



### In this Notebook I try to claasfiy the handwritten Arabic characters


### Data source: https://www.kaggle.com/mloey1/ahcd1

### I use following libraries <ul>

<li> Keras </li>

<li> Numpy </li>
<li> Matplotlib </li>

<li> pandas </li>
</ul>



### The archetcure I use for the CNN is:   Conv1 --> BatchNormz --> Conv2 --> BatchNormz --> Maxpool --> Dropout  Conv3 --> BatchNormz --> Conv4 --> BatchNormz --> Maxpool --> Dropout  Conv5 --> BatchNormz --> Conv6 --> BatchNormz --> Maxpool --> Dropout  --> Flatten --> FC7 


#### Hyperparameters
<li> Optmizer: Adam </li>
<li> Cost Function: CrossEntropy </li>
<li> batch size: 128 </li>
<li> epoch:100 </li>
<li> Learning Rate:0.001 </li>

</ul>
