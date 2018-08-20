# Refinery Decoking Prediction

The initial attempts at predicting decoking periods of refinery furnaces based on data (2017-11 to 2018-07) from process engineers.
The goal is to help engineers take active control of possible imminent decoking and therefore help reduce the costs due to shut-down of the furnaces.


## Prerequisites
Models:
* [scikit-learn]
* [keras]
* [tensorflow]

Plots:
* [seaborn]
* [matplotlib]
* [plotly]
* [pdpbox]

Tuning:
* [sigopt]

Generic: 
* [Numpy]
* [pandas]
* [datetime]
* [simplejson]
* [csv]
* [pickle]
* [math]


## How it works

* The idea, simply, is to predict VPR(venturi pressure) for 20 passes of the furnaces. If any of them is over 0.95, then it indicates decoking needs. 
* We are utilizing two approaches: Long short term memory(LSTM) and Gradient boosting (GBM) for the prediction.
* The raw data: time stamped data of lots of variables stored in XOP, ndP, VPR, Flow, Temperature, Decoke, FireboxandDMDS, Analyzers, Severity sheets in the excel file

 ![refineryrawdata](C:/Users/Ginny.Zhu/OneDrive - Shell/AArefinary/Pics/refineryrawdata.png)



slight changes in terms of output locations after re-organization 
But naming should be self-evident to find out, so please double check.

this step does this 

that step does that

with outputs like these 


```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Organization of the files 

Explain how to run the automated tests for this system

## To-dos

Explain what these tests test and why

```
Give an example
```


## Authors

* **Ginny Zhu** - *Initial work* - [githubprofile](https://github.com/chocolocked)


## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* Thank you all wonderful people at Shell that make my intership extra amazing
* etc

check out here(https://www.npmjs.com/package/convert-md) 

**Coded by Ginny, with love :)**
