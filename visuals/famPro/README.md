Family Promise Visual Dashboard

Required Libraries:

[dev-packages]
jupyter = "*"
pytest = "*"

[packages]
fastapi = "*"
sqlalchemy = "*"
numpy = "*"
pandas = "*"
jupyter = "*"
jupyterlab = "*"
matplotlib = "*"
plotly-express = "*"
seaborn = "*"
scikit-learn = "*"
category-encoders = "*"
joblib = "*"
psycopg2-binary = "*"
streamlit = "*"
shap = "*"
pdpbox = "*"
catboost = "*"
awesome-streamlit = "*"
pyowm = "*"

[requires]
python_version = "3"

[packages.uvicorn]
extras = [ "standard",]
version = "*"

[packages.pandas-profiling]
extras = [ "notebook",]