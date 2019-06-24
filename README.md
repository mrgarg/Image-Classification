# Image-Classification
Image classification is the process of taking an input (i.e. picture) and outputting a class (i.e. “cat”) or a probability that the input is a particular class (for example: there’s a 90% probability that this input is a cat).

Self-driving cars are a great example to understand where image classification is used in the real-world.

in this model 4 types of different images are used (cats,dogs,humans,horses) for training. Each category having 200 approx examples.

### different steps are involved in the building of this model:
1) dataset preparation using pathlib and keras which involve loading the image and conversion into numpy array.
2) visualization using matplotlib.
3) building of support vector machine classifier from scratch.
4) use of one vs one technique for multiclass classification.
5) training nC2 models(n is the total number of classes)because one vs one technique is used.
6) prediction on test sample
7) comparison of score from above model with scikit-learn inbuilt svm classifier model.
