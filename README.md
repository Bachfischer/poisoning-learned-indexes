# poisoning-learned-indexes

## Project structure

* `data/` -- Various datasets
* `doc/` -- Documentation
* `playground/` -- Random experiments
* `src/` -- Source code for experiments


## Research questions

### How much poisoning is enough? 

Vary the number of poisonous keys and looking what happens with the accuracy
- Can we say anything based on the data set etc. e.g. "I will need this amount of new keys (at minimum) to make the distribution off".

Approach: 
- Specify the dataset
- Perform poisoning on leaf models by varying posioning threshold (p = 0.05, ... , 0.2)

### Understand effects of non-linear models

## Cheatsheet

Connection to SOSD Benchmark server (with n=8 CPUs, e2-standard-8):

```
ssh -i .ssh/google_compute_engine bachfischer@130.211.197.90
```

SSH access to GitHub on SOSD Benchmark server:
```
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/sosd_benchmark
```
