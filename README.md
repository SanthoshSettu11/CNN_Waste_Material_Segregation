# CNN_Waste_Material_Segregation

## **Objective**

The objective of this project is to implement an effective waste material segregation system using convolutional neural networks (CNNs) that categorises waste into distinct groups. This process enhances recycling efficiency, minimises environmental pollution, and promotes sustainable waste management practices.

The key goals are:

* Accurately classify waste materials into categories like cardboard, glass, paper, and plastic.
* Improve waste segregation efficiency to support recycling and reduce landfill waste.
* Understand the properties of different waste materials to optimise sorting methods for sustainability.


#### Findings from the data

#### Number of classes: 7

#### Class labels: 0 to 6
{'Cardboard': 0, 'Food_Waste': 1, 'Glass': 2, 'Metal': 3, 'Other': 4, 'Paper': 5, 'Plastic': 6}


#### Image size: 
Resized to (224, 224, 3)


#### Model Training Results

##### Model Trained with

Optimizer: Adam

Loss Function: SparseCategoricalCrossentropy (from logits)

Batch size: 32

Epochs: 30

##### Model accuracy

accuracy: 0.5641 - loss: 1.1975
