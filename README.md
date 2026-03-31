## Linear Regression From Scratch

This project is about building linear regression from scratch using NumPy. I did not use any machine learning libraries. The goal was to understand how the model actually works step by step.

## Approach

I started by loading the house price dataset which contains area, number of rooms, and price. To keep things simple, I used only the area to predict the price.
I created a simple equation where price depends on area. Then I trained the model using gradient descent. In each step, the model updates its values to reduce the error.
I also normalized the data so the training becomes stable and does not break.

## Difficulties faced

At first, the loss was increasing instead of decreasing, which made the model unstable.
When I removed normalization, I got overflow errors and the values became very large. The model stopped working properly.
I also faced a small error while loading the dataset.

## Resolutions

Normalizing the data and correcting the learning rate fixed the loss and overflow issue.
the dataset issue was fixed by placing the CSV file in the same folder as the notebook.

## Results

After training the model, the loss started decreasing steadily, which shows that the model was learning properly.
The final equation gives a clear relationship between area and price based on the data.

## Learnings

1. I understood the concepts of linear regression.
2. I learned how gradient descent updates the model step by step.

## How to run this project

1. Download or clone this repository
2. Make sure the CSV file and notebook are in the same folder
3. Install required libraries
4. Open Jupyter Notebook
5. Run all the cells in order

