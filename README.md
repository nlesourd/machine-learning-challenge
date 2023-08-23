# Machine learning competition

As part of a machine learning course, we ran a competition with the aim of obtaining the best accuracy on a given problem.

## Goals

The objective is to design a machine learning model to predict the category of images of Fashion-Mnist dataset. The available dataset are in train.csv which includes the images and their labels.
The evaluation will be performed on a test set which labels are not disclosed. You have at disposal only the test images in test_inputs.csv. Run your prediction model on the test images. The obtained predictions are to be formatted (see Evaluation part) and submitted in a file submission.csv. Your score on the test set will be automatically computed. Only one submission is allowed per day.

## Learning outcomes

- Know how to perform data loading using Python tools
- Explore and pre-process gray images
- Extract (or learn) features if necessary
- Perform multiclass classification

## The rules

- Set down a team of 2. The team’s name should guy1_guy2
- A team is allowed one submission per day. The achieved score on a subset of the test
samples is released online in a temporary leaderboard
- The final leaderboard will be released at completion of the challenge ; it will be
composed of the final scores on the remaining test samples
- Deliverables on Moodle: commented script explaining the implemented method and the
learning procedure. The script should be named as follows: guy1_guy2.extension

## Methods used

- ACP
- SVM with rbf kernel
- Gridsearch

## Final score

precision: 0.89760
score: 9/19


## Further information

Available on https://www.kaggle.com/competitions/fastfashion/overview