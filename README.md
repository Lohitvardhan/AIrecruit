# Recruit.ai

This project automates the first round of recruitment by replacing traditional resumes with candidate introduction videos. Emotional analysis is conducted on the videos using LLAVA to assess engagement and expressions, while the video transcripts are analyzed to extract key details like qualifications, skills, and experience. Based on these insights, an automated decision is generated to determine whether the candidate advances to the next round.

## Run the webapp
1. Clone this repository
2. You can run below command in windows so that it will install necessary python libraries
```
  pip install -r requirements.txt

```
3. Create an .env file with the following data
```
  LLAVA_ENDPOINT = "<your_llava_endpoint_url>"

```
4. Finally, run the Flask app
```
  python app.py

```

