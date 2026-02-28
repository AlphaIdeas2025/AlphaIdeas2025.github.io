# AlphaIdeas2025.github.io

## GPT version in use

This site uses **OpenAI `gpt-4o`** — the multimodal GPT-4o model.

| Property | Value |
|---|---|
| Model ID | `gpt-4o` |
| Provider | OpenAI |
| Family | GPT-4o (multimodal) |
| Context window | 128,000 tokens |
| Knowledge cutoff | October 2023 |
| API endpoint | `https://api.openai.com/v1/chat/completions` |

The live model version is confirmed at runtime: after each API call the `model` field returned in
the response is read and displayed in the UI, so you always see the exact version string OpenAI
reports for that request.