# Lecture Note of 21/11/2024

- other classical hypothesis
    - residuals v.s. fitted values
        - see noises
        - see diff of y to get an insight
            - independent from x
    

- confidence
    - e.g.
        - $y=\mu_a | \mu_b + v_c | v_d + \epsilon$
    - type 1 error
        - multiple comparison
    - ANOVA (ANalysis Of VAriance)
        - idea of R square

- typical case studies
    - determining which variables are most influential on the response
    - Devicse an analytical model ofthe response y as a function of the primary factors
    - fit a an analytical model like regression
    - taguchi desgin?

- general workflow
    - divide reponsibilities like software engineering
    - R DoE library
    - csv file with the list of experiments to run
    - experiment engine
        - script that reads (input_csv) and outputs (data and meta-data)
    - data and **meta-data** for each experiments
    - csv file with the experiment results
    - R

- example
    - environemnt
    - physical metrics
        - memory
        - cpu
    - time
    - collect as much information as possible
        - it will be worth when something weired with the experiments.
