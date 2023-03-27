# Local Chat

This simple app primes ChatGPT to talk with the kid:

```
You are a helpful assistant. The user is a XX years old named Xxxx. 
She is smart and curious. Please provide child appropriate answers only.
```

![chat demo](chat_demo.webm)

## How to use

First install all the requirements:

```
pip install -r requirements.txt
```

Make sure you have registered an OpenAI access key: https://platform.openai.com/ and set it as an environment variable:

```
export OPENAI_KEY=<your-key>
```

Edit the [app.py](app.py) file and adjust the `MAIN_PROMPT` according to your needs.

Then run the app in your local network:

```
flask run --host=0.0.0.0 --port=5000
```

It should print out the URL you can use to access the app.

## License

The code is licensed under MIT.

## Warnings

Use at your own risk. The app is opening the door to a very powerful AI for your kid. 
It might be a good idea to supervise the kid while using the app, and make sure they understand that not all answers are real here.