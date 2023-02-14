# 🦜️🔗 LangChain.js

⚡ Building applications with LLMs through composability ⚡

**Production Support:** As you move your LangChains into production, we'd love to offer more comprehensive support.
Please fill out [this form](https://forms.gle/57d8AmXBYp8PP8tZA) and we'll set up a dedicated support Slack channel.

## Quick Install

`yarn add langchain.js --ignore-optional`

**Note**: You should also make sure you have `moduleResolution` set to `nodenext` in your
`tsconfig.json` if you're using ESM modules and would like to import from subpaths of langchain like

```typescript
import { OpenAI } from 'langchain.js/llms';
```

## 🤔 What is this?

Large language models (LLMs) are emerging as a transformative technology, enabling
developers to build applications that they previously could not.
But using these LLMs in isolation is often not enough to
create a truly powerful app - the real power comes when you can combine them with other sources of computation or knowledge.

This library is aimed at assisting in the development of those types of applications.

## Relationship with Python LangChain

This is built to integrate as seamlessly as possible with the [LangChain Python package](https://github.com/hwchase17/langchain). Specifically, this means all objects (prompts, LLMs, chains, etc) are designed in a way where they can be serialized and shared between languages.

## 📖 Documentation

Documentation for Typescript is still WIP. In the meantime you can see the
full Python documentation [here](https://langchain.readthedocs.io/en/latest/?)


## 💁 Contributing

As an open source project in a rapidly developing field, we are extremely open to contributions, whether it be in the form of a new feature, improved infra, or better documentation.

Check out [our contributing guidelines](CONTRIBUTING.md) for instructions on how to contribute.
