# AN2DL-challenge2

## What is
This is the repository which contains the submission to the second challenge of the course **Artificial Neural Networks and Deep Learning** at Politecnico di Milano.

Challenge 2 - Team name: **Dead_Neurons**
University: **Politecnico di Milano, Laurea Magistrale (MSc) - Computer Science and Engineering**

## How the competition works
We had 2 weeks during the semester to develop notebooks related to Neural Networks. The role of this Network is to perform time series forecasting. The zipped dataset was given us from the professors. They kept a private test set for scoring models. The metric used to compute a "leaderboard" is the Root Mean Squared Error (RMSE). We could participate to the challenge in groups of 3.
The Leaderboard was just for us, the main purpose of this challenge (competition) is to explore the world of Image Classification, and to gain more experience as possible in this field.
**DISCLAIMER**: We know that using multiple times the same dataset is wrong (because, using it multiple times results in being biased with respect to it). We used the remote test set many times, only because was the first time that we were approaching NNs, and hence we treated it more like a "validation set".

The zipped file of the dataset just contained a folder, named "train", in which there were time series samples. Pre processing (as splitting in folders, or any other kind of augmentation on images) was left to us. We had to develop different techniques in order to make prediction with the time series (such as *attention*), and to exploit different approaches.

## Our Team
- Luca Alessanrini  
- Luca Venturini (added as collaborator)
- Ruggiero Ronzulli (added as collaborator)

## How we divided the work
We concorded together three different approach to this problem. Everyone developed one of them, and we communicated in order to decide how to move. Main ideas were concorded together, and applied to the chosen approach.

## How to replicate our results
Be careful when running the notebook. Often, also from the same author, the path to the folders (both for checkpoints, testing, or loading images) changes, due to the fact that we may run the notebook in a different environment. Please, **adjust your folder path** according to your system. We mainly used Google Colab with Google Drive.

## Where are all the commits?
Unfortunately, since we worked with Google Colab (hence, on Google Drive), we had no time to keep a copy of every single change also on GitHub, hence we decided to put here only the submission folder as a main reference.

## Submission
We had to submit all the scripts we (eventually) used, all the notebooks commented, and a final report of maximum 3 pages, explaining the approach we followed

## Score
The exam was scored in this way:
- 20 points of written exam
- 5 + 0.5 points of challenge 1
- 5 + 0.5 points of challenge 2

The two challenges had 0.5 points of bonus for well done works in order to be able to reach 31 and get the laude.

In this challenge we got all the points (5.5).
