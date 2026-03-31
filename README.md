## Linear Regression From Scratch

This project is about building linear regression from scratch using NumPy. I did not use any machine learning libraries. The goal was to understand how the model actually works step by step.

## Approach

I started by loading the house price dataset which contains area, number of rooms, and price. To keep things simple, I used only the area to predict the price.
I created a simple equation where price depends on area. Then I trained the model using gradient descent. In each step, the model updates its values to reduce the error.
I also normalized the data so the training becomes stable and does not break.

## Difficulties faced

At first, the loss was increasing instead of decreasing, which made the model unstable.
When I removed normalization, I got overflow errors and the values became very large. The model stopped working properly.
It was also confusing to understand how the values of m and b are updated during training.
I also faced a small issue while loading the dataset due to incorrect file placement.

## Resolutions

I fixed the loss and overflow issue by normalizing the data and choosing a proper learning rate.
I understood the updates by observing how the values change step by step during training.
I fixed the dataset issue by placing the CSV file in the same folder as the notebook.

## Results

The loss decreases smoothly over epochs, which shows that the model is learning correctly.
The final equation represents the relationship between area and price after training.

## Learnings

I learned how linear regression works internally instead of using libraries.
I understood how gradient descent updates the model step by step.
I also learned that normalization is very important for stable training.

## How to run this project

1. Download or clone this repository
2. Make sure the CSV file and notebook are in the same folder
3. Install required libraries:
4. Open Jupyter Notebook:
5. Run all the cells in order

You will get the loss vs epoch graph and the final learned equation.
