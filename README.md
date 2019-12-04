# DS_Challenge

## Nov 30
Add train_test_split and feature_label_split functions.








###############################################################################

## Oct 22 (yuesong)
Initiate a git repo and add project description and original dataset. This is created to manage merger issue.

Data exploration, cleaning, feature selection, and convert UTM into lon/lat. I will set up Google API the next time.

## Oct 22 (ziyue)
pull request:
https://kbroman.org/github_tutorial/pages/fork.html

syncing a forked repo:
https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/syncing-a-fork

update commit email ☑️

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
4. delete rows with values of -99 (refer to Q&A)

## Oct 25(Qing)
one-hotencoding

## Oct 26(Qing)
standardization

## Oct 27(Qing)
Define other 3 functions for fitted model(randon forest /NN/SVM)
Will try to do feature engineering tmr,(consider more features: e.g. proxmity to schools; get neighbourhood data; crime rate by neighbourhood)

## Oct 30 (yuesong)
some exploration on how to read dbf, kml and other 4 files with diff extensions. Seems all 6 files provide same information. included a few quick-start example. delete whenever they become useless.

to visually see the data
1. open Google Earth
2. go to settings to allow import file
3. import .kml file
4. great visual

## Oct 30 (ziyue)
- shapefile extensions: https://en.wikipedia.org/wiki/Shapefile 
- GIS with Python and geopandas tutorial (nice read!): https://www.earthdatascience.org/workshops/gis-open-source-python/intro-vector-data-python/
- three key files: .shp, .shx, .dbf; the rest can be ignored for now
- bdf shp shx dfs are the same, use one will do

1. add kml support to geopandas
2. to be resolved: kml dataframe missing attributes other than geometry
3. utf-8 encoding for spanish characters
4. static zone visualization

## Nov 30 (ziyue)
1. EDA
2. re-run distance matrix using my own API key

## Dec 1 (ziyue)
1. EDA done, feature engineering tmr

## Dec 2/3 (ziyue)
1. feature engineering done

## Dec 4 (ziyue)
1. prediction done (left NN)

## Dec 5 (ziyue)
1. NN done
2. contribution done
3. final wrap-up

## to do:
1. one-hot encoding ☑️
2. standardization ☑️
3. feature engineering
4. random forest / NN / SVM / etc. ☑️
5. consider more features: e.g. proxmity to schools; get neighbourhood data; crime rate by neighbourhood