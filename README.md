# NLP_assignment_2
Develop a basic probabilistic parser for French that is based on the CYK algorithm and the PCFG model and that is robust to unknown words.



## Installing requirements.
To run the code, follow those steps:

Install requirements (in the repository):

```
pip install -r requirements.txt
```

## Launching the parser
### To run the parser on the test_corpus 

```
bash run.sh --train-size 0.8 --val-size 0.1 --test-size 0.1 --bigram-coef 0.2
```
