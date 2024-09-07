## Malaria Detection
**The context:** Why is this problem important to solve?<br>

Malaria is a long-standing problem, especially in places with tropical weather and poor sanitation. Early detection and treatment is cruicial in reducing the spread and mortality rate from the infection. Until now, there was no option but to rely on off-site laboratory based manual inspection and diagnosis of histology images. The amount of time and effort spent on this tedious process could be better utilized in other areas if this process could be automated. Along with traditional digital image processing, Deep Learning promises to reliably automate this process. It is important to refine ML and DL models to get as accurate a process as we can.

**The objectives:** What is the intended goal?<br>

Intended goal here is to create and test various model architetures of Convolutional Neural Networks and assess which one has the best accuracy on test data. We need to look at not just the raw accuracy numbers but also the Confusion Matrix in order to select the best model.

**The key questions:** What are the key questions that need to be answered?<br>

1) What kind of CNN architecture yields the best, most reliable outcome?<br>
2) What are the elements that go into a model and what fine-tuning is required in each model? <br>
3) What is the effect of preprocessing the data? <br>
4) Are the results and metrics of a model in line with what is normally expected of a CNN architecture? <br>

**The problem formulation:** What is it that we are trying to solve using data science? <br>

We are trying to analyze histopathology images of uninfected and infected images and create a workflow that automatically identifies infected images as accurately and reliably as possible. For this, we are using supervised learning with labeled data set and convolutional neural network architecture. The problem eventually is of Binary Classification type.


## <b>Data Description </b>

There are a total of 24,958 train and 2,600 test images (colored) that we have taken from microscopic images. These images are of the following categories:<br>


**Parasitized:** The parasitized cells contain the Plasmodium parasite which causes malaria<br>
**Uninfected:** The uninfected cells are free of the Plasmodium parasites<br>
