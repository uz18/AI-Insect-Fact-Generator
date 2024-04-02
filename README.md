### AI-Insect-Fact-Generator (Client)
Webpage which uses the Hugging Face and Pixabay API to create a unique insect fact, inference the insect name from the generated fact, and find a real image to go alongside it

https://uz18.github.io/AI-Insect-Fact-Generator

Please note that the actual logic is handled on a separate webserver in an attempt to mask my API keys, keep in mind that this may add some time to your initial request after periods of inactivity

Model used for fact generation - https://huggingface.co/mistralai/Mixtral-8x7B-Instruct-v0.1

Model used for insect name inferencing - https://huggingface.co/google-bert/bert-large-uncased-whole-word-masking-finetuned-squad

Javascript is required to run this webpage in a basic attempt to prevent spam. No cookies are stored on your device, and no identifiable information is collected.
To see a more indepth and secure antispam solution I am working on check out https://github.com/uz18/antiSpam-POC
