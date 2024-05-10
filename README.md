# Crop Disease Detection using Image Classification on Leaves - Soft Computing

## Objective:

The objective of this project is to develop an algorithm that utilizes deep learning, image processing, and fuzzy inference systems to identify diseases caused by various microorganisms infesting plant leaves. Additionally, the algorithm estimates the health severity of the leaf based on the extent of infection.

[![Flow Chart](https://user-images.githubusercontent.com/73630123/119841897-d5ffbe00-bf23-11eb-8b50-85d662d42d7a.jpg)](https://youtu.be/N7Jr5pAZFg8)

## Methodology:

### I. Neural Network Classifier

A neural network classifier is employed to categorize leaf images into one of five categories: Bacteria, Fungi, Virus, Nematode, and Normal Leaf (no infection).

![Infected Leaf Samples](https://user-images.githubusercontent.com/73630123/119844591-3132b000-bf26-11eb-8151-0c4dc690b854.png)

After classification, feature extraction of the infected leaf is performed using digital image processing techniques.

### II. Image Processing

The images in the dataset are analyzed to understand the various patterns in which organisms infect leaves. Image processing techniques are then used to extract the infected area of the leaf, isolating it from the background and the healthy green parts.

![Image Processing](https://user-images.githubusercontent.com/73630123/119844877-6ccd7a00-bf26-11eb-94ed-bf3a323f05ee.jpg)

### III. Fuzzy Rule Base System

To determine the health severity of the leaf as a percentage, a set of rules is aggregated using a Fuzzy Inference System implemented in MATLAB.

![Fuzzy Rule Base System](https://user-images.githubusercontent.com/73630123/119845058-95ee0a80-bf26-11eb-93ee-cfed52f258bd.jpg)

## Result:

![Result Discussion](https://user-images.githubusercontent.com/73630123/119840931-04c96480-bf23-11eb-957d-14e49c01d3d9.jpg)

## Group Members:

1. Jhupaka Ranjit (2020IMT-042)
2. Praveen Kumar Choudhary (2020IMT-072)
3. Priyanshu (2020IMT-076)
4. Shivam Saraswat (2020IMT-091)
5. Sourabh Chandel (2020IMT-102)
6. Vidhu Prakash (2020IMT-115)

Presentation Link: [Prezi](https://prezi.com/view/b1jEjud6gS1f5gRcdBsl/)

Overleaf Report Link: [Overleaf](https://www.overleaf.com/9935637858wttpsvcxnxjw#8c253f)
