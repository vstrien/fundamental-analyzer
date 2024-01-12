# Fundamental Analyzer

Simple script to let OpenAI do a screening of an earnings call.
In order to start, you need two environment variables, which you could store into a .env-file:

* AZURE_OPENAI_ENDPOINT
* AZURE_OPENAI_KEY

Of course, you could use the non-Azure OpenAI keys / endpoints as well. 
You probably need ChatGPT4-32K in order to handle an entire earnings call.

## Wishlist

- [ ] Rework into command-line script
- [ ] Embed into a web app that can easi(er) be used
- [ ] Have the option to upload audio files as well (use whisper)
- [ ] Test if this can also be achieved with embeddings (to let you ask multiple questions about an earnings call while remaining grounded in the factual information)
- [ ] Add embeddings (or attach vector database) for adding all kinds of other information, for example:
  - Fundamental (historical) information
  - Earlier earnings calls
  - Other kinds of forms
- [ ] Integrate with the [Fundamental Club](https://github.com/vstrien/fundamentalclub)