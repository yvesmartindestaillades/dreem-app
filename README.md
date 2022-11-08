# DREEM app

GitHub repo for DREEM DMS-MaPseq analysis online tool: https://dreem-app.herokuapp.com/


## Installation + run the app with dummy data

```
cd path/to/where/you/want/dreem-app
git clone https://github.com/yvesmartindestaillades/dreem-app
cd dreem-app
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python3 app.py
```

Then open http://127.0.0.1:8050/ in a web navigator, and use data.csv as a dummy dataset.
