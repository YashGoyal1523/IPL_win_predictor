// to deploy on heroku

create

requirements.txt

runtime.txt ->
Python 3.10.19

Procfile->
web: streamlit run app.py --server.port=$PORT --server.address=0.0.0.0


then deploy