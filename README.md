# Smart Campus Analytics Streamlit App

Put these files in the same folder/repository as `app.py`:
- `Cleaned_Student_Dataset.csv`
- `random_forest_model.pkl`
- `preprocessor.pkl`

The model and preprocessor must come from the same training workflow. The deployed scikit-learn version should be compatible with the version used to save them.

## Deploy
1. Create a GitHub repository.
2. Upload `app.py`, `requirements.txt`, and the required dataset/model files.
3. Visit https://share.streamlit.io/ and sign in with GitHub.
4. Select your repository, branch, and `app.py`, then deploy.

Privacy: do not put student names, IDs, or private records in a public repository. Use anonymized data for a public demo.

## Run locally
`python -m pip install -r requirements.txt`
`python -m streamlit run app.py`
