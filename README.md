# Lecture material for the Oxford DTC essential maths and stats course

Other material, including solutions to problem sheets, is in the private repository here:
<https://github.com/fcooper8472/DtcMathsStats2018>


### Install dependencies

It is assumed that you have Python 3 installed on your machine.

```bash
python3 -m venv venv
source venv/bin/activate
pip install --upgrade pip setuptools wheel
pip install -r requirements.txt
```

Run with:

```bash
voila --template=reveal --VoilaConfiguration.resources="{'reveal': {'theme': 'serif'}}" .\lecture-02-indices-logs.ipynb
```
