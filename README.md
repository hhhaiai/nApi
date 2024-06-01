# xpo

## 地址一: https://huggingface.co/spaces/chatgptbots/2

```


curl 'https://chatgptbots-2.hf.space/api/openai/v1/chat/completions' \
  -H 'accept: application/json, text/event-stream' \
  -H 'content-type: application/json' \
  -H 'cookie: _ga=GA1.2.1021110946.1717239337; _gid=GA1.2.657788509.1717239338; _ga_R1FN4KJKJH=GS1.1.1717239337.1.1.1717239605.0.0.0' \
  -H 'origin: https://chatgptbots-2.hf.space' \
  -H 'referer: https://chatgptbots-2.hf.space/' \
  -H 'user-agent: Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/125.0.0.0 Safari/537.36' \
  --data-raw $'{"messages":[{"role":"system","content":"\\nYou are ChatGPT, a large language model trained by OpenAI. Don\'t use emojis all the time.\\nKnowledge cutoff: 2021-09\\nCurrent model: gpt-3.5-turbo\\nCurrent time: Sat Jun 01 2024 19:03:09 GMT+0800 (中国标准时间)\\nLatex inline: \\\\(x^2\\\\) \\nLatex block: $$e=mc^2$$\\n\\n"},{"role":"user","content":"你是谁"}],"stream":true,"model":"gpt-3.5-turbo","temperature":0.5,"presence_penalty":0,"frequency_penalty":0,"top_p":1}'


curl 'https://chatgptbots-2.hf.space/api/openai/v1/chat/completions' \
  -H 'accept: application/json, text/event-stream' \
  -H 'content-type: application/json' \
  -H 'cookie: _ga=GA1.2.1021110946.1717239337; _gid=GA1.2.657788509.1717239338; _ga_R1FN4KJKJH=GS1.1.1717239337.1.1.1717239605.0.0.0' \
  -H 'origin: https://chatgptbots-2.hf.space' \
  -H 'referer: https://chatgptbots-2.hf.space/' \
  -H 'user-agent: Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/125.0.0.0 Safari/537.36' \
  --data-raw $'{"messages":[{"role":"system","content":"\\nYou are ChatGPT, a large language model trained by OpenAI. Don\'t use emojis all the time.\\nKnowledge cutoff: 2021-09\\nCurrent model: gpt-3.5-turbo\\nCurrent time: Sat Jun 01 2024 19:03:09 GMT+0800 (中国标准时间)\\nLatex inline: \\\\(x^2\\\\) \\nLatex block: $$e=mc^2$$\\n\\n"},{"role":"user","content":"你是谁"}],"stream":false,"model":"gpt-3.5-turbo","temperature":0.5,"presence_penalty":0,"frequency_penalty":0,"top_p":1}'


```

## 地址二: https://huggingface.co/spaces/narra-ai/ChatGPT

* 包含模型:  gpt-4-turbo-preview、Creative、Balanced、Precise、gpt-3.5-turbo-16k

```

curl 'https://narra-ai-chatgpt.hf.space/api/openai/v1/chat/completions' \
  -H 'accept: application/json, text/event-stream' \
  -H 'accept-language: en-US,en;q=0.9,zh-CN;q=0.8,zh;q=0.7' \
  -H 'content-type: application/json' \
  -H 'cookie: _ga=GA1.2.1021110946.1717239337; _gid=GA1.2.657788509.1717239338; _ga_R1FN4KJKJH=GS1.1.1717239337.1.1.1717239605.0.0.0' \
  -H 'origin: https://narra-ai-chatgpt.hf.space' \
  -H 'referer: https://narra-ai-chatgpt.hf.space/' \
  -H 'user-agent: Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/125.0.0.0 Safari/537.36' \
  --data-raw $'{"messages":[{"role":"system","content":"\\nYou are ChatGPT, a large language model trained by OpenAI. Don\'t use emojis all the time.\\nKnowledge cutoff: 2023-12\\nCurrent model: gpt-4-turbo-preview\\nCurrent time: Sat Jun 01 2024 19:06:05 GMT+0800 (中国标准时间)\\nLatex inline: \\\\(x^2\\\\) \\nLatex block: $$e=mc^2$$\\n\\n"},{"role":"user","content":"你的上下文是多少"}],"stream":true,"model":"gpt-4-turbo-preview","temperature":0.5,"presence_penalty":0,"frequency_penalty":0,"top_p":1}'



curl 'https://narra-ai-chatgpt.hf.space/api/openai/v1/chat/completions' \
  -H 'accept: application/json, text/event-stream' \
  -H 'accept-language: en-US,en;q=0.9,zh-CN;q=0.8,zh;q=0.7' \
  -H 'content-type: application/json' \
  -H 'cookie: _ga=GA1.2.1021110946.1717239337; _gid=GA1.2.657788509.1717239338; _ga_R1FN4KJKJH=GS1.1.1717239337.1.1.1717239605.0.0.0' \
  -H 'origin: https://narra-ai-chatgpt.hf.space' \
  -H 'referer: https://narra-ai-chatgpt.hf.space/' \
  -H 'user-agent: Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/125.0.0.0 Safari/537.36' \
  --data-raw $'{"messages":[{"role":"system","content":"\\nYou are ChatGPT, a large language model trained by OpenAI. Don\'t use emojis all the time.\\nKnowledge cutoff: 2023-12\\nCurrent model: gpt-4-turbo-preview\\nCurrent time: Sat Jun 01 2024 19:06:05 GMT+0800 (中国标准时间)\\nLatex inline: \\\\(x^2\\\\) \\nLatex block: $$e=mc^2$$\\n\\n"},{"role":"user","content":"你的上下文是多少"}],"stream":false,"model":"gpt-4-turbo-preview","temperature":0.5,"presence_penalty":0,"frequency_penalty":0,"top_p":1}'

```

## 模型三: https://huggingface.co/spaces/KingNish/OpenGPT-4o

## 模型四: https://huggingface.co/spaces/ehristoforu/dalle-3-xl-lora-v2

