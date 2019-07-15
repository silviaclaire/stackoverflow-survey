# stackoverflow_survey
A data analysis project using 2017–2019 StackOverflow Developer Survey Results.

## Project Motivation
The purpose of this project is to implement the CRISP_DM process and data wrangling skills with real-life datasets.

## Dependencies
- python 3.7
- jupyter notebook
- numpy
- pandas
- matplotlib

## Project Structures
```yaml
- dataset/
  - developer_survey_2017/
    - survey_results_public.csv
    - ...
  - developer_survey_2018/
    - survey_results_public.csv
    - ...
  - developer_survey_2019/
    - survey_results_public.csv
    - ...
- StackOverflow_Survey.ipynb
```

`dataset/`: A folder used to store 2017–2019 StackOverflow Developer Survey Results. 
NOTICE: Due to GitHub's [100 MB push limit](https://help.github.com/en/articles/conditions-for-large-files#100-mb-push-limit), you will have to download the data from [here](https://insights.stackoverflow.com/survey), extract the archives and place them following the project structure above.

`StackOverflow_Survey.ipynb`: A jupyter notebook inluding all necessary project code. 

## A Brief Summery of Analysis Results
1. We counted the proportion of individuals working with particular languages , and compare the rankings in each year. It showed that the most popular language has been **JavaScript**. Up-trending languages include **Go**, **Rust**, **Clojure**, **F#** and **Erlang**.

2. We then looked at how different languages relate to job satisfaction. We found that **TypeScript** and **Bash/Shell** have good rankings in terms of job satisfaction these years. Steady increase in job satisfaction was observed in **Clojure**, **Ruby**, **Go**, **R**, **Rust** and **Erlang**.

3. Finally, we investigate which languages most people choose as their starting points by counting the proportion of individuals with a 0–5 years of coding experience. The top-5 languages in recent years are **Assembly** and **Matlab(2017–2018)**.
