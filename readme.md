# Python OpenAI API Test

---

## .env

---

```json
OPENAI_API_KEY=''
OPENAI_MODEL='gpt-3.5-turbo'
OPENAI_MAX_TOKENS=1000
OPENAI_TEMPERATURE=0
OPENAI_ORGANIZATION=''
```

`OPENAI_API_KEY` is OpenAI Account API Key.

`OPENAI_MODEL` is model that api use.

`OPENAI_MAX_TOKENS` is messages read token values. \
More info on [Tokenizer](https://platform.openai.com/tokenizer)

`OPENAI_TEMPERATURE` is the sampling temperature, between 0 and 2. Higher values like 0.8 will make the output more random, while lower values like 0.2 will make it more focused and deterministic.

`OPENAI_ORGANIZATION` is OpenAI Account's Organization value.