<!-- font: frutiger -->

### Bayesian Statistics I (aka Bayesian Learning)

![](https://github.com/mattiasvillani/BayesLearnCourse/raw/master/Slides/Images/BayesTheoremNeon.jpg "Bayesian Learning")

\

<div style="background-color:#eaeff7; padding:20px 47px;">

### Aims

The course aims to give a solid introduction to the Bayesian approach to statistical inference, with a view towards applications in data mining and machine learning. After an introduction to the subjective probability concept that underlies Bayesian inference, the course moves on to the mathematics of the prior-to-posterior updating in basic statistical models, such as the Bernoulli, normal and multinomial models. Linear regression and nonlinear regression are also analyzed using a Bayesian approach. The course subsequently shows how complex models can be analyzed with simulation methods like Markov Chain Monte Carlo (MCMC) or approximate methods like Variational Inference. Bayesian prediction and marginalization of nuisance parameters is explained, and introductions to Bayesian model selection and Bayesian decision theory are also given.
</div>

\

<div style="background-color:#eaeff7; padding:20px 47px;">

### Course literature and Schedule

The course will use the following book as the main course literature:

* Gelman, Carlin, Stern, Dunson, Vehtari, Rubin (2014).
Bayesian Data Analysis. Chapman & Hall/CRC: Boca Raton, Florida. 3rd edition.
* My slides on this page
* Additional course material linked from this page, such as articles and tutorial.\\

The course schedule on TimeEdit is here: [Schedule](https://cloud.timeedit.net/su/web/stud1/ri157XQQ684Z50Qv17043gZ6y1Y7006Q5Y65Y3.html).

</div>

\

<div style="background-color:#eaeff7; padding:20px 47px;">

### Computer labs

* The computer labs is a central part of this course and you should expect to allocate substantial time for each lab. Many of the exam questions will be computer based, so working on the labs will also help you with the exam.
* You are strongly encouraged to do the labs in R, but any programming language is ok to use.
* The labs should be done in pairs of students. 
* Each lab report should be submitted as a PDF along with the .R file with code. Submission is done through the Mondo system.
* There is only two hours of supervised time allocated to each lab. This will not be enough time to complete each lab. The idea is that you should start working on the lab before the computer session, so that you are in a position to ask questions at the session.

</div>

\


<div style="background-color:#eaeff7; padding:20px 47px;">

### Teachers

##### Lecturer
[Mattias Villani](https://mattiasvillani.com) \
Professor \
Department of Statistics, Stockholm University \
Division of Statistics and Machine Learning, Linköping University 

##### Lab assistants
[Oscar Oelrich](https://www.su.se/english/profiles/ooelr-1.342298) \
PhD Candidate \
Department of Statistics, Stockholm University \\

[Munezero Parfait](https://www.su.se/english/profiles/pmune-1.218608) \
PhD Candidate \
Department of Statistics, Stockholm University 

</div>

\
<div style="background-color:#eaeff7; padding:20px 47px;">

#### Part 1 - The Basics
**Lecture 1** - Basics concepts. Likelihood. The Bernoulli model.\
Reading: BDA Ch. 1, 2.1-2.5 |  [Slides](SLIDES) \
Code: Beta density | Bernoulli model | One-parameter Gaussian model

**Lecture 2** - Gaussian model. Conjugate priors. The Poisson model. Prior elicitation. Noninformative priors.\
Reading: BDA Ch. 2.6-2.9 | [Slides](SLIDES) 

**Lecture 3** - Multi-parameter models. Marginalization. Multinomial model. Multivariate normal model.\
Reading: BDA Ch. 3 | [Slides](SLIDES) \
Code: Two-parameter Gaussian model | Prediction with two-parameter Gaussian model | Multinomial model

**Exercise session 1** \
Exercises: TBA \
Assistant: [Munezero Parfait](https://www.su.se/english/profiles/pmune-1.218608) 

**Computer Lab 1** - Exploring posterior distributions in one-parameter models by simulation and direct numerical evaluation.\
Lab: Lab1 \
Assistant: [Munezero Parfait](https://www.su.se/english/profiles/pmune-1.218608) \
Submission tool: Mondo.

</div>
\

<div style="background-color:#eaeff7; padding:20px 47px;">

#### Part 2 - Bayesian Regression and Classification
**Lecture 4** - Prediction. Making Decisions.\
Reading: BDA Ch. 9.1-9.2. | [Slides](SLIDES) \
Code: 

**Lecture 5** - Linear Regression. Nonlinear regression. Regularization priors.\
Reading: BDA Ch. 14 and Ch. 20.1-20.2 | [Slides](SLIDES)  \
Code: 

**Lecture 6** - Classification. Posterior approximation. Logistic regression. Naive Bayes.\
Reading: BDA Ch. 16.1-16.3 | [Slides](SLIDES) \
Code:

**Exercise session 2** \
Exercises: TBA \
Assistant: [Oscar Oelrich](https://www.su.se/english/profiles/ooelr-1.342298)

**Computer Lab 2** - Polynomial regression and classification with logistic regression.\
Lab: Lab2 \
Assistant: [Oscar Oelrich](https://www.su.se/english/profiles/ooelr-1.342298) \
Submission tool: Mondo.
</div>

\
<div style="background-color:#eaeff7; padding:20px 47px;">

#### Part 3 - More Advanced Models, MCMC and Variational Bayes
**Lecture 7** - Bayesian computations. Monte Carlo simulation. Gibbs sampling. Data augmentation. \
Reading: BDA Ch. 10-11 | [Slides](SLIDES) \
Code:

**Lecture 8** - MCMC and Metropolis-Hastings \
Reading: BDA Ch. 11 | [Slides](SLIDES) \
Code:

**Lecture 9** - HMC, Variational Bayes and Stan. \
Reading: BDA Ch. 12.4 and Ch. 13.7 | [RStan vignette](https://cran.r-project.org/web/packages/rstan/vignettes/rstan.html) | [Slides](SLIDES) \
Code:

**Computer Lab 3** - Gibbs sampling for the normal model, mixture of normals and probit regression. \
Lab: Lab3 \
Assistant: [Munezero Parfait](https://www.su.se/english/profiles/pmune-1.218608) \
Submission tool:  Mondo.

</div>

\
<div style="background-color:#eaeff7; padding:20px 47px;">

#### Part 4 - Model Inference and Variable Selection
**Lecture 10 - Bayesian model comparison.**\
Reading: BDA | [Slides](SLIDES) \
Code: 

**Lecture 11** - Computing the marginal likelihood, Bayesian variable selection, model averaging.\

Reading: BDA | [Slides](SLIDES) \
Code: 

**Lecture 12** - Model evaluation and course summary.\
Reading: BDA | [Slides](SLIDES) \
Code: 

**Computer Lab 4** - Metropolis-Hastings for Poisson regression.\
Lab: Lab4 \
Assistant: [Oscar Oelrich](https://www.su.se/english/profiles/ooelr-1.342298) \
Submission tool:  Mondo.
</div>

\
<div style="background-color:#eaeff7; padding:20px 47px;">

#### Examination

The course examination consists of:

* Written lab reports (deadlines will be given in Mondo)
* Take home exam:
    - 1st attempt: handed out on January 14. To be returned on January 18.
    - 2nd attempt: handed out on TBD. To be returned on TBD.
</div>
\