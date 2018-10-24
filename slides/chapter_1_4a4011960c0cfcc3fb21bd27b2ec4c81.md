---
title: Insert title here
key: 4a4011960c0cfcc3fb21bd27b2ec4c81

---
## INTRODUCTION TO GENERALIZED LINEAR MODELS

```yaml
type: "TitleSlide"
key: "d4e499f551"
```

`@lower_third`

name: Ita Cirovic Donev
title: Chief Data Scientist


`@script`



---
## Data and Methods

```yaml
type: "FullSlide"
key: "470f96555a"
```

`@part1`
Methods of statistical analysis vs. various scales of data measurement
- responses measured are statistically independent random variables
- explanatory variables: categorical and/or continuous
  
| Response    	| Example                                     	| Method                           	|
|-------------	|---------------------------------------------	|----------------------------------	|
| Continuous  	| `height, weight`                              | Multiple regression              	|
| Binary      	| `True, False`                         	| Logistic regression              	|
| Counts      	| number of times an event occurs               | Poisson regression               	|
| Multinomial 	| `red, green, blue` 	                        | Multinominal logistic regression 	|
| Ordinal     	| `(1-10),(10-20), (>20)`                       | Ordinal logistic regression      	|


`@script`
Let's start with an overview of how response and explanatory variables are measured. Consider the following table.

iid rv except the GEE method which are not scope of this course

The models in this course involve a single response variable and a single and/or several explanatory variables.

Don't forget that before any statistical analysis of data we should always first gain understanding of data and check data quality and make assurances that the values are plausible. For example, we can ask questions such as


---
## A little reminder....

```yaml
type: "FullSlide"
key: "6491e9aca6"
```

`@part1`
- What is the scale of data measurement? Continuous? Binary? Categorical?
- If it categorical, how many levels does it have?
- Are the level nominal or ordinal?
- How are variables associated?
- What is the shape of the distribution?


`@script`
- How are variables associated? - scatterplots for continuous, cross-tabulations for categorical, box plots for grouped variables with continuous scale measurements. Are the relationships linear, nonlinear.


---
## Generalized Linear Models

```yaml
type: "TwoColumns"
key: "c1ef15167e"
```

`@part1`
$E(Y_i) = \mu_i = \bold{x_i^T\beta}$  
where $Y_i \sim N(\mu_i, \sigma^2) $


`@part2`
- link function
-


`@script`



---
## Final Slide

```yaml
type: "FinalSlide"
key: "8022c77ae9"
```

`@script`


