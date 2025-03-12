# Pizza Object Detector > Pizza Object Detector Roboflow 3.0 Model
https://universe.roboflow.com/advanced-computer-vision-assignment/pizza-object-detector

Provided by a Roboflow user
License: CC BY 4.0

# Overview

The object detection process required an annotated pizza dataset sourced from a Kaggle repository [1], comprising approximately **9000** pizza images capturing diverse visual conditions and angles. Around **1500** images were randomly selected and meticulously annotated with **16** ingredient labels, encompassing common pizza components like Cheese, Pepperoni, and Basil. Utilizing RoboFlow, a versatile dataset creation tool, facilitated label management, bounding box creation, and image sorting, streamlining the annotation process. The dataset was split into training, validation, and testing subsets **(60%, 20%, and 20% respectively)**, ensuring a comprehensive evaluation. Augmentations like rotation and blur, applied exclusively to the training set, increased its size to **2544** images, while the validation and testing sets contained **284** and **283** images respectively. This dataset underwent extensive preparation and augmentation, laying the groundwork for subsequent model training and evaluation phases. RoboFlow's visual aids provided valuable insights into dataset characteristics, including label representation and object placement within images.

The following is a list of classes used for annotation:

1. Arugula
2. Bacon
3. Basil
4. Broccoli
5. Cheese
6. Chicken
7. Corn
8. Ham
9. Mushroom
10. Olives
11. Onion
12. Pepperoni
13. Peppers
14. Pineapple
15. Pizza
16. Tomatoes


[1] M. Bryant, Pizza images with topping labels,
https://www.kaggle.com/datasets/michaelbryantds/pizza-images-with-topping-
labels/, Jun. 2019. 