# physics-classification
This project was developed as a prototype for future advanced video classification applications in schools or laboratories.

---

We tested the model using two classification classes:

#### Free Fall

![Free Fall](https://raw.githubusercontent.com/ratikaewkam/physics-classification/refs/heads/main/img/Freefall.png)

#### Sound vs Fire

![Sound vs Fire](https://raw.githubusercontent.com/ratikaewkam/physics-classification/refs/heads/main/img/SoundvsFire.png)

We designed three different neural network models by varying the activation functions, the number of layers, and the number of neurons.
All three models achieved 100% accuracy, but the third model had the fewest parameters, making it the fastest in terms of computation and prediction speed.

### Results
We divided the dataset into four folders: training, testing, validation, and unseen.
- During training and testing, all models performed without any issues.
- However, when we used unseen data—especially videos captured from different camera perspectives (e.g., different zoom levels)—the models struggled to make accurate predictions.
- If the perspective and setup of the unseen video matched the training or testing conditions, the models could still predict correctly, even if that exact video had never been used before.

### Next Steps
In the next phase, I will collaborate with three high school students. I will build the base model, and they will apply it in real-world scenarios. For example, they will integrate the model with a Raspberry Pi.
As for me, if time permits, I plan to explore new approaches to neural network design.

### Credits
- Model Development & Owner of the Sound vs. Fire Dataset: ([Rati Kaewkam](https://github.com/ratikaewkam))
- Raspberry Pi Integration & Owners of the Free Fall Dataset: (Three high school students)