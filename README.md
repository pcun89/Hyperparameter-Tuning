# Hyperparameter-Tuning
The raisin classification problem is used as a hands-on way to explore how model performance can be improved through tuning. The dataset includes detailed measurements of raisins—such as area, perimeter, and eccentricity—and the task is to correctly classify them into categories like Kecimen or Besni.

To achieve this, learners apply machine learning algorithms such as Decision Trees, Random Forests, and Support Vector Machines. Each of these models comes with adjustable settings, called hyperparameters, that control how the algorithm learns from the data. Unlike model parameters, which are learned during training, hyperparameters must be set beforehand. Choosing the right values can significantly affect accuracy and generalization.

The course introduces two systematic approaches for finding optimal hyperparameters:

Grid Search, which exhaustively tests every possible combination of specified values, ensuring a thorough exploration of the parameter space but often requiring more computational time.

Random Search, which instead samples from defined distributions of hyperparameters, allowing faster experimentation while still discovering strong candidates for performance improvement.

By experimenting with these methods on the raisin dataset, learners see firsthand how thoughtful hyperparameter tuning transforms a basic model into a much more accurate and reliable classifier. This practical example makes the abstract idea of hyperparameter optimization tangible and shows how it can be applied to real-world datasets.