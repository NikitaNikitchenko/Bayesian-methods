# Байесовские методы

Данный проект был выполнен мною в рамках семестрового курса «Байесовские методы» (3 курс ВМК МГУ, 2021г)

Проект заключается в анализе датасета с помощью обобщенной линейной модели и техники MCMC (Markov Chain Monte Carlo). 

**Data**: https://www.kaggle.com/arashnic/hr-analytics-job-change-of-data-scientists?select=aug_train.csv

**Description**:
Компания, которая занимается Big Data и Data Science хочет нанять специалистов по данным среди людей, которые успешно проходят курсы, проводимые компанией. Многие люди записываются на обучение, но кто из этих кандидатов действительно хочет работать в компании после прохождения курсов?

**Target**: Вероятность того, что кандидат будет работать на компанию после прохождения курсов 

**Features**: 13 признаков, указанных в анкете кандидатом (есть количественные, порядковые, бинарные, номинальные) 

**Model**: Логистическая регрессия (для бинарной классификации).
