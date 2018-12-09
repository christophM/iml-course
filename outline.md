# Outline

Each bullet point will be a video with about 10 minutes. min 3, max 15.
Titles are for chapters.


## Introduction

- What is machine learning? Examples, mental models and terminology. learner vs. model

- What is the problem with machine learning? Black box. 

- Examples for lack of interpretability: Asthma example, Huskey vs. Wolf, ...

- When we need interpretability, when we don't 


## What tools do we have?

- Overview over techniques.

- White box models. Overview, examples.

- Post-hoc interpretability methods. Overview, examples, can be combined with white box.


## Linear models

- lm
- sparse lm
- SLIM
- additional methods for linear models: effects, importance


## Decision Trees

- Tree structure, CART
- Something newer
- feature importance


## Rule-based approaches

- OneR
- Overview over approaches: lists vs. sets, ...
- SBRL
- RuleFit


## Post-hoc Feature effects

- general idea, naive approach (average predictions), mental model of marginal effect
- PDP and ICE
- Problems with PDP, ICE. solution M-Plots? no.
- ALE Plots

## post-hoc feature importance

- permutation importance
- PIMP
- variance based importance

## post-hoce explanation of predictions

- LIME
- Shapley
- SHAP
- Counterfactuals
