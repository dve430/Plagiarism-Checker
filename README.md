
# Shivesh Dave (190001057)
# Plagiarism Checker 

In today's environment, the internet is the answer to every query. As a result, anyone, at any time, can easily copy and use content from the internet. Plagiarism is the phrase used to describe this. It's currently growing. People plagiarise things by rewording, copying, and omitting to cite sources in the majority of situations. This web application makes use of We'll create a Python Flask programme that searches for potentially duplicated material using Pinecone, a similarity search engine.'

Python 3.9+, Flask 2.0+, and Pinecone were used to create this project. It uses the Pinecone SDK to run a similarity search to identify articles with the same or similar content as the user's input.

## Running the app locally

Begin by cloning this git repo and navigating to the project directory.

Next, create a virtual environment and activate it:

```
python -m venv venv
. venv/bin/activate
```

Install dependencies by running:

```
python -m pip install -r requirements.txt
```

Create an `.env` file and add your Pinecone API key:

```
PINECONE_API_KEY=your-key-here
```

Finally, to run the app on your machine, simply run this command from the terminal:

```
flask run
```

Or, to run the app in debug mode, add the `FLASK_ENV=development` environment variable before the command:

```
FLASK_ENV=development flask run
```

The app should now be running on http://127.0.0.1:5000 in your browser.

Dataset
- https://www.kaggle.com/snapcrack/all-the-news
