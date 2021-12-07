# Predicting Frequency of Extramarital Affairs

## Team members

* Jun Won (Lakon) Park 
* Sarah Li


## Description of the data 

There are 601 observations from a survey conducted by Psychology Today in 1969.

### Response variable

The response variable is **affairs**, representing how often the individual engaged in extramarital sexual involvements in the past year. (0 = none, 1 = once, 2 = twice, 3 = 3 times, 7 = 4–10 times, 12 = monthly or more often)

### Predictor variables

There are 8 predictor variables. The survey conducted collected information in ranges for simplicity. 

**Categorical variables**: 

- Sex (0 = female, 1 = male)

- Children (0 = no, 1 = yes)

**Oridinal variables**:

- Age (17.5 = under 20, 22 = 20–24, 27 = 25–29, 32 = 30–34, 37 = 35–39, 42 = 40–44, 47 = 45–49, 52 = 50–54, 57 = 55 or over)

- Years married (0.125 = 3 months or less, 0.417 = 4–6 months, 0.75 = 6 months–1 year, 1.5 = 1–2 years, 4 = 3–5 years, 7 = 6–8 years, 10 = 9–11 years, 15 = 12 or more years)

- Religiousness (5 = very, 4 = somewhat, 3 = slightly, 2 = not at all, 1 = anti)

- Level of education (9 = grade school, 12 = high school graduate, 14 = some college, 16 = college graduate, 17 = some graduate work, 18 = master's degree, 20 = Ph.D., M.D., or other advanced degree)

- Occupation rating (1-7 according to a [classification scale](https://dictionary.fitbir.nih.gov/portal/publicData/dataElementAction!view.action?dataElementName=HollingsheadJobClassCat&publicArea=true) of socioeconomic status of workers, reverse numbered)

- Marriage rating (5 = very happy, 4 = happier than average, 3 = average, 2 = somewhat unhappy, 1 = very unhappy)

## Precise description of the question(s)

- How do certain related predictors influence whether they will be involved in an affair? eg. Variables contributing to:
   - Marriage stability or "sunk-cost" of a marriage: years married, children, marriage satisfaction
   - Socioeconomic status: education level, occupation rating

- What are the most important factors in determining if an individual is involved in an extramarital affair? We would like to explore correlation between variables and model using the best predictors. 

- Using the best predictors we can find, can we create a model that can predict if an individual has been involved in extramarital affairs? Can we also effectively predict the frequency of affairs?

## Why this question/dataset

It would be interesting to explore what influences people to become involved in extramarital affairs. We often speculate about certain predictors being the cause, so we would like to confirm our speculations with real data. 

We would also like the ability to predict whether our future spouses are involved in affairs. If our future spouses are involved in extramarital affairs, we would like to use a model to predict the frequency of involvement.

## Reading list 
- [R documentation for the dataset](https://www.rdocumentation.org/packages/AER/versions/1.2-9/topics/Affairs)
- [Journal containing analysis of affairs data](https://fairmodel.econ.yale.edu/rayfair/pdf/1978a200.pdf)
- [An Analysis of Fair’s Extramarital Affairs Data](http://rstudio-pubs-static.s3.amazonaws.com/513142_c1db279047d04ee6803dc0acdbfcb5bd.html)
- [CMU homework assignment using the affairs data](https://www.stat.cmu.edu/~cshalizi/402/hw/08/hw-08.pdf)

(papers you may need to read)
