# Invisible in the Classroom

**Gender Differences in Sense of Belonging and Participation in Education**

An independent research project at St. Lawrence University asking whether men and women feel different levels of belonging in undergraduate classrooms, and whether belonging predicts how much students participate.

**Harper Eskey**, Data Science · **Advisor:** Professor Jennifer Hansen, Philosophy · St. Lawrence University · Spring 2026

## Background

In *Invisible Women* (2019), Caroline Criado Perez documents how the systematic exclusion of women from data collection has shaped everything from crash test dummies to medical research, with consequences that range from inconvenient to fatal. Her central argument is that this gap is not the product of malice but of structural oversight: men go without saying, and so women do not get said at all. Higher education is no exception.

If classrooms are built around an implicit male default, women's experiences of those spaces may differ in ways that are real but rarely counted. Sense of belonging is one such dimension: difficult to observe, easy to overlook, and potentially consequential for who speaks up, persists, or eventually leaves.

## Research questions

1. Do men and women differ significantly in sense of belonging within undergraduate classrooms?
2. Is belonging correlated with other classroom experiences, such as perceptions of grading, group dynamics, and instructor preference?
3. Does sense of belonging predict classroom participation?

## Data

* **Participants:** 68 undergraduate students across departments at St. Lawrence University
* **Final sample after cleaning:** 59 (22 men, 37 women)
* Non-binary and gender non-conforming participants were excluded from group comparisons due to insufficient sample size.

### Measures

Six scales, each rated 1 to 5 (higher means a more positive experience):

| Scale | What it captures |
|---|---|
| Belonging | How connected and welcome students feel in the classroom |
| Participation | How often students engage and speak up |
| Grading | Perceptions of grading |
| Group Dynamics | Experiences working with peers |
| Instructor Preference (least preferred) | Experience with their least preferred instructor |
| Instructor Preference (preferred) | Experience with a preferred instructor |

Assessing instructor preference twice allows a comparison between lived and desired classroom experience.

## Methods

* **Gender differences:** Welch's t-test, confirmed with a Mann-Whitney U test
* **Associations between scales:** Pearson correlations
* **Belonging and participation:** OLS regression
* **Assumption checks:** Shapiro-Wilk (normality) and Levene's test (equal variance)

## Key findings

### 1. Men reported a stronger sense of belonging than women

| Group | Mean belonging |
|---|---|
| Men | 3.78 |
| Women | 3.44 |

The difference was statistically significant (p = .022) with a medium effect size (Hedges' g = 0.63). **Belonging was the only one of the six measures to differ significantly by gender.**

Men's scores clustered between 3.5 and 4.0 with a median around 3.75. Women's scores were more spread out, with a lower median and a longer tail reaching down toward 2.5.

### 2. Belonging sits at the center of the classroom experience

Belonging was positively correlated with every other measure. Its strongest association was with participation (r = 0.61, p < .001), the strongest correlation in the dataset.

### 3. Belonging predicts participation

Belonging was the strongest predictor of participation, accounting for **37% of its variance**. Adding grading and group dynamics did not meaningfully improve the model.

The relationship held at nearly the same slope for men and women. What differed was where each group started: women clustered toward lower belonging, which corresponded to
