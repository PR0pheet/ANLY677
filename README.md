# ANLY677 Group4

**Abstract**

  Assisted driving is a concept that has appeared since the 1990s, and this concept has been widely studied in the past decade with the advancement of technology. And the specific part we focus on is the traffic light recognition plate in assisted driving. At present, two common traffic light recognition methods are V2X (signal interaction between the car computer and the built-in device of the traffic light) and 2D image detection. Based on the high cost and high implementation difficulty of V2X, we focus our research on 2D image detection which is easier to construct. After a Literature Review of mainstream academic articles, we found that some of the diversity of traffic lights in this field is missing (such as arrows, countdowns, waiting to turn, etc.), so we decided to make up for this missing detail. We trained AlexNet, VGG, ResNet, and Inception models using about 500 images (including red, green, yellow, directions, and various uncommon shapes of traffic lights) from unsplash, google, and multiple locations. Although on the whole, AlexNet, VGG and ResNet have their own advantages in different color prediction, in the end of the four CNN models, we think that the ResNet model has the best performance, because its Top1 Accuracy is 86.9% and The Top5 Accuracy of 99.31% is the highest value among the four models. Based on the results obtained, we believe that our data type is efficient and that the fit of these data to various models is considerable. As the number and diversity of datasets increase, our model will be better at judging traffic light types and will make up for the temporary lack of detail in this field.


**Introduction** 

  The earliest assistant driving systems appeared in the 1930s. Although the technology was immature at the time, it can be seen that human interest in assistant driving has emerged since then. For example, the existing lane change reminder, the reminder of deviation from the main road, and the detection of traffic lights are also assistant driving applications that people actively explore. Traffic light detection systems are still in the developmental stage in assisted driving. Previously, Tesla has seen cases of "recognizing the tail light of a truck as a traffic light" and "recognizing the moon as a yellow light." This shows that we still need to improve on this technology. We looked at a lot of previous studies. While they used a lot of analysis, most of them only used traditional traffic lights (no directions, no countdowns, or even more complex signs), so we hope this part of the content is to complement and make traffic The light detection system can detect and define a broader range of traffic lights.
 
