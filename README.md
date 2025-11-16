# Mark on Spacy and Text-Fabric

This simple Natural Language Processing (NPL) study on Mark, greek, perform the following analysis on the greek text of Mark:

- Verbs: the top 5
- Verbs Tense Analysis (past, present, future, pluperfect)
- Verbs Mood Analysis (indicative, imperative, subjunctive, conditional, optative)
- Verbs Voices Analysis (active, passive, middle)
- Verbs Subjects Analysis for `λέγω`
- Present Participle Verbs Analysis (Non-Finite Forms)
- Analysis of Verbal "Chaining" (Control Verbs)

## Prerequisites (macOs)

### Python, PIP, Requirements Installation (spacy, odycy...)

```
cd ~
mkdir tmp
cd tmp
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
python3 get-pip.py
/Library/Developer/CommandLineTools/usr/bin/python3 -m pip install --upgrade pip
pip3 install -r requirements
```

### Run Jupyter
```bash
jupyter lab
```

## Resources
- [Mark, Greek text](https://raw.githubusercontent.com/Faithlife/SBLGNT/refs/heads/master/data/sblgnt/text/Mark.txt), from the Greek New Testament, SBL Edition (SBLGNT, Society of Biblical Literature NT)
- [odyCy](https://centre-for-humanities-computing.github.io/odyCy/getting_started.html), a general-purpose NLP pipeline for Ancient-Greek.
