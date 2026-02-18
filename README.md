# DA4 - Module 5

## Notebook 1
add encoding:

`staging = pd.read_csv(GCS_URL, encoding='latin1')`

## Notebook 3
Possible pip install:

`!pip install --upgrade google-cloud-bigquery pandas-gbq -q`

## Google Authentication

When Colab authenticates to GCP it asks for access to:

- Google Drive - because Colab saves notebooks to Drive
- Email/profile - to identify which Google account is authenticating, so GCP knows who is making the BigQuery requests

Learners should just click Allow. It's not actually reading their emails - it just uses the email address as the identity to check against your IAM settings in the project.
