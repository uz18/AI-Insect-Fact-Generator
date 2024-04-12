# AI-Insect-Fact-Generator (Client)
Webpage which uses the Hugging Face and Pixabay API to create a unique insect fact, infer the insect name from the generated fact, and find a real image to go alongside it

### [https://uz18.github.io/AI-Insect-Fact-Generator](https://uz18.github.io/AI-Insect-Fact-Generator)

Please note that the actual logic is handled on a separate web server in an attempt to mask my API keys; this may add some time to your initial request during periods of inactivity

## Sources
- The model used for fact generation - [https://huggingface.co/mistralai/Mixtral-8x7B-Instruct-v0.1](https://huggingface.co/mistralai/Mixtral-8x7B-Instruct-v0.1)
- The model used for insect name inferencing - [https://huggingface.co/google-bert/bert-large-uncased-whole-word-masking-finetuned-squad](https://huggingface.co/google-bert/bert-large-uncased-whole-word-masking-finetuned-squad)
- Images are fetched from - [https://pixabay.com/api/docs/](https://pixabay.com/api/docs/) 

## Requirements
Javascript is required to run this webpage in order to prevent spam.

As of 4/11/2024
- it supports Chrome, Firefox, Safari, Opera, Edge, and Brave (with shields disabled)
- it blocks PuppeterJS (including extra-stealth), Selenium (incl. Driverless), NoDriver, Playwright (incl. stealth), TOR, and more!
To see a more in-depth explanation of how this anti-spam solution works, see [https://github.com/uz18/antiSpam-POC](https://github.com/uz18/antiSpam-POC)
