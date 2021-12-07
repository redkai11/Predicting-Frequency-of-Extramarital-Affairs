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

**Quantitative variables**:

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
## Team contract. 

For each area, write 1-2 sentences and including any rules to which your team collectively agrees (e.g. "We agree to make 1 commit per week." or "We agree to meet in the library every other Friday.")

**Participation**  
We agree to commit regularly and put in effort to meet deadlines. We will communicate any obstacles to completing project checkpoints as soon as we are aware of them.

**Communication**  
We agree to respond to each other's messages within 3 hours, unless any emergencies occur. 

**Meetings**  
We agree to meet up to twice a week before lectures. If we are unable to meet in person, we can meet on Messenger or Zoom.

**Conduct**  
We agree to be respectful to each other. 

***
Do not make any changes from here on. Only the TAs will edit the following.


# Checkpoint 1 grade

(5 / 5)



# Checkpoint 2 grade

__Total__ (28/ 30)

__Words__ (6 / 6) The text is laid out cleanly, with clear divisions
and transitions between sections and sub-sections. The writing itself
is well-organized, free of grammatical and other mechanical errors,
divided into complete sentences logically grouped into paragraphs and
sections, and easy to follow from the presumed level of knowledge. 

__Numbers__ (1 / 1) All numerical results or summaries are reported to
suitable precision, and with appropriate measures of uncertainty
attached when applicable. 

__Pictures__ (6/ 7) Figures and tables are easy to read, with
~informative captions~, axis labels and legends, and are placed near the
relevant pieces of text or referred to with convenient labels. 

__Code__ (3 / 4) The code is formatted and organized so that it is easy
for others to read and understand. It is indented, commented, and uses
meaningful names. It only includes computations which are actually
needed to answer the analytical questions, and avoids redundancy. ~Code
borrowed from the notes, from books, or from resources found online is
explicitly acknowledged and sourced in the comments.~ Functions or
procedures not directly taken from the notes have accompanying tests
which check whether the code does what it is supposed to. The text of
the report is free of intrusive blocks of code. With regards to R Markdown,
all calculations are actually done in the file as it knits, and only
relevant results are shown.

__Exploratory data analysis__ (12 / 12) Variables are examined individually and
bivariately. Features/observations are discussed with appropriate
figure or tables. The relevance of the EDA to the questions and
potential models is clearly explained.

__Comment__
1. https://learning.github.ubc.ca/STAT-406-101-2021W/project-konathanbaconjr/blob/611a29941ad570227219d950f9b3868cdb99ba2e/report.Rmd#L19 this is technically a categorical variable depsite being codes as numbers. 
2. https://learning.github.ubc.ca/STAT-406-101-2021W/project-konathanbaconjr/blob/611a29941ad570227219d950f9b3868cdb99ba2e/report.Rmd#L127 this plot probably needs a caption to explain what it is counting. 

# Checkpoint 3 grade

__Total__ (65 / 65)

__Words__ (8 / 8) The text is laid out cleanly, with clear divisions and
transitions between sections and sub-sections.  The writing itself is
well-organized, free of grammatical and other mechanical errors, divided into
complete sentences logically grouped into paragraphs and sections, and easy to
follow from the presumed level of knowledge.

__Numbers__ (1 / 1) All numerical results or summaries are reported to
suitable precision, and with appropriate measures of uncertainty attached when
applicable.

__Pictures__ (7 / 7) Figures and tables are easy to read, with informative
captions, axis labels and legends, and are placed near the relevant pieces of
text.

__Code__ (4 / 4) The code is formatted and organized so that it is easy
for others to read and understand.  It is indented, commented, and uses
meaningful names.  It only includes computations which are actually needed to
answer the analytical questions, and avoids redundancy.  Code borrowed from the
notes, from books, or from resources found online is explicitly acknowledged
and sourced in the comments.  Functions or procedures not directly taken from
the notes have accompanying tests which check whether the code does what it is
supposed to. The text of the report is free of intrusive blocks of code.  If
you use R Markdown, all calculations are actually done in the file as it knits,
and only relevant results are shown. 

__Exploratory Data Analysis__ (12 / 12) Variables are examined individually and
bivariately. Features/observations are discussed with appropriate
figure or tables. The relevance of the EDA to the questions and
potential models is clearly explained.

__Results and analysis__ (25 / 25) The statistical summaries
are clearly related to, or possibly derive from, the substantive questions of interest.  Any
assumptions are checked by means of appropriate diagnostic plots or
formal tests. Limitations from un-fixable problems are
clearly noted. The actual estimation
of parameters, predictions, or other calculations are technically correct.  All calculations
based on estimates are clearly explained, and also technically correct.  All
estimates or derived quantities are accompanied with appropriate measures of
uncertainty. 

__Conclusions__ (8 / 8) The substantive questions are answered as
precisely as the data and the model allow.  The chain of reasoning from
estimation results about models, or derived quantities, to substantive
conclusions is both clear and convincing.  Contingent answers ("if $X$, then
$Y$, but if $Z$, then $W$") are likewise described as warranted by the
and data.  If uncertainties in the data mean the answers to some
questions must be imprecise, this too is reflected in the conclusions.
