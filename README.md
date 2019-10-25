# DS_Challenge

## Oct 22 (yuesong)
Initiate a git repo and add project description and original dataset. This is created to manage merger issue.

Data exploration, cleaning, feature selection, and convert UTM into lon/lat. I will set up Google API the next time.

## Oct 22 (ziyue)
pull request:
https://kbroman.org/github_tutorial/pages/fork.html

syncing a forked repo:
https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/syncing-a-fork

update commit email

## Oct 23 (yuesong)
Google Map API is set up. Distance and time taken are requested and appended into the data-frame. Cleaned data are exported as a new csv data-frame.

## Oct 24 (ziyue)
1. headings and subheadings; documentation
2. add section on checking missing values
3. (tbc later tonight) EDA
4. modify Qing's codes 

## Oct 24 (Qing)
Define 3 functions for fitted model(logisticregression,knn and linear regression)

## Oct 25 (Ziyue)
according to the Q&As, the following changes have been made:
1. download zones shapefiles
2. retain EXCLUIR column
3. remove the travel time by car to city centre data obtained from Google API
4. -99

## to do:
1. one-hot encoding
2. standardization
3. feature engineering
4. random forest / NN / SVM / etc.
5. consider more features: e.g. proxmity to schools; get neighbourhood data; crime rate by neighbourhood