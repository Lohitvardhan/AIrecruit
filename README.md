# Recruit.ai

Automating first round selections in recruitment process. As an alternative to resumes, candidates are supposed to send introduction videos. Emotional analysis would be performed on these videos using LLaVa. Their transcript would be analyzed to get the details of the candidate. Finally, a decision would be given on whether to select the candidate or not.

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

