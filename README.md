# shop-mate

An AI-powered commerce engine for convenient and affordable shopping.

![capture](/public/shop_iphone.png)

> [!NOTE]
> Please note the official the official website [shop-mate.io](https://shop-mate.io). The official website will be updated with additional features such as authentication, which are necessary for providing the service online. We are on the journey of building an efficient and convenient shopping!

## 🗂️ Overview

- 🛠 [Features](#-features)
- 🧱 [Stack](#-stack)
<!-- - 🚀 [Quickstart](#-quickstart)
- 🌐 [Deploy](#-deploy)
- 🔎 [Search Engine](#-search-engine) -->
- ✅ [Verified models](#-verified-models)

## 🛠 Features

- Shop for specific products using shop-mate
- Summarized and useful product information
- Retrieve products from specified/desired stores or shops
- Search history functionality
- Share search results ([Optional](https://github.com/miurla/morphic/blob/main/.env.local.example))
- Video search support ([Optional](https://github.com/miurla/morphic/blob/main/.env.local.example))
- Helpful product feedback and reviews * [※](#-search-engine)
- Support for providers other than OpenAI
  - Google Generative AI Provider [※](https://github.com/miurla/morphic/issues/192)
  - Anthropic Provider [※](https://github.com/miurla/morphic/pull/239)
  - Ollama Provider ([Unstable](https://github.com/miurla/morphic/issues/215))
- Specify the model to generate answers
  - Groq API support [※](https://github.com/miurla/morphic/pull/58)

## 🧱 Stack

- App framework: [Next.js](https://nextjs.org/)
- Text streaming / Generative UI: [Vercel AI SDK](https://sdk.vercel.ai/docs)
- Generative Model: [OpenAI](https://openai.com/)
- Search API: [Tavily AI](https://tavily.com/) / [Serper](https://serper.dev)
- Reader API: [Jina AI](https://jina.ai/)
- Serverless Database: [Upstash](https://upstash.com/)
- Component library: [shadcn/ui](https://ui.shadcn.com/)
- Headless component primitives: [Radix UI](https://www.radix-ui.com/)
- Styling: [Tailwind CSS](https://tailwindcss.com/)

## ✅ Verified models

### List of models applicable to all:

- OpenAI
  - gpt-4o
  - gpt-4-turbo
  - gpt-3.5-turbo
- Google
  - Gemini 1.5 pro [※](https://github.com/miurla/morphic/issues/192)
- Ollama (Unstable)
  - mistral/openhermes & Phi3/llama3 [※](https://github.com/miurla/morphic/issues/215)

### List of verified models that can be specified to writers:

- [Groq](https://console.groq.com/docs/models)
  - LLaMA3.1 8b
  - LLaMA3.1 70B
  - LLaMA3 8b
  - LLaMA3 70b
