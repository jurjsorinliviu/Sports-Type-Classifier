# 22 Types of Sports Classification

Following are the types of sports over which we are trying to classifying:
-   Swimming 
-   Badminton     
-   Wrestling 
-   Olympic Shooting 
-   Cricket 
-   Football 
-   Tennis 
-   Hockey 
-   Ice Hockey
-   Kabaddi 
-   WWE 
-   Gymnasium 
-   Weight lifting 
-   Volleyball 
-   Table tennis 
-   Baseball     
-   Formula 1 
-   Moto GP 
-   Chess 
-   Boxing 
-   Fencing 
-   Basketball

### Data Distribution
Data has been downloaded with the help of [gi2ds](https://github.com/toffebjorkskog/ml-tools/blob/master/gi2ds.md)

Training set: 11524
Validation set: 2881

### Model
Resnet-50

### Data Augmentations
The following data augmentation has been applied to increase the no of images in the training set

1.  Flip horizontal
2.  Lighting
3.  Zooming
4.  Warping

### Confusion Matrix

Pair of confused categories with minimum value of 2
[('motogp', 'formula1', 5),
('badminton', 'tennis', 4),
('weight_lifting', 'wrestling', 3),
('wrestling', 'wwe', 3),
('badminton', 'table_tennis', 2),
('basketball', 'volleyball', 2),
('boxing', 'wrestling', 2),
('hockey', 'ice_hockey', 2),
('kabaddi', 'hockey', 2),
('tennis', 'table_tennis', 2),
('weight_lifting', 'wwe', 2),
 ('wrestling', 'kabaddi', 2)]
 
### Sample Images from the confused categories:

For some images you can see the prediction is correct but the manual labelling was done wrong. This shows the CNN are less susceptible to human mistakes.

### Accuracy
The accuracy obtained is 97%

### Heatmap

Original Image

After Heatmap


