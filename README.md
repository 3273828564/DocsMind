# Chat-Markdown

Chat-Markdown is an open-source project that allows you to chat with your markdown files.

![Stack](https://skillicons.dev/icons?i=vite,react,ts,tailwind,flask)

## Demo

[Demo Site](https://chat-markdown.alanwang.site/)

Deploy on Vercel and Railway

> **Warning**
>
> Due to the free plan of Railway only providing 500 hours per month, the Demo on the 21st day of each month will not be available. Please clone it locally for use at that time.

## Features

- 🤖 Chat with your markdown files
- 📝 Summarize articles
- 🖍️ Highlight source
- 📤 Upload files
- 💾 Data saved locally
- 💰 Token usage tracker
- 🐳 Dockerize

## Future Development

I plan to add the following features in the future:

- [ ] Support for more file formats: pdf, txt
- [ ] Download doc from the internet
- [ ] Markdown-formatted message
- [ ] i18n
- [ ] Desktop application

If you find this project helpful, please consider giving it a star 🌟

## Q&A

### How to run locally?

> **Warning**
>
> Please check if you can access OpenAI in your region, you can refer to the [issue](https://github.com/3Alan/chat-markdown/issues/3#issuecomment-1511470063) for more information.

1. Create .env

Create a `.env` file and copy the contents of `.env.example` to modify it.

2. Run App

```bash
docker-compose up -d
```

Please add `--build` to rebuild the image after each code update.

```bash
docker-compose up -d --build
```

now you can access the app at `http://localhost:8081`

### Local Development

<details>
  <summary>Detail</summary>

#### Create .env

Create `.env` file and fill in environment variables, see `.env.example` for reference

#### Run Frontend

1. Install dependencies

```
yarn
```

2. Run app

```
yarn dev
```

#### Run Backend

you need a python environment

1. Create virtual environment

```
cd server
python -m venv .venv
```

2. Active virtual environment

windows

```
.venv\Scripts\activate
```

mac

```
. .venv/bin/activate
```

3. Install dependencies

```
pip install -r requirements.txt
```

4. Run Services

```
flask run --reload --port=8080
```

</detail>

## Buy me a coffee

<img height="300" src="https://raw.githubusercontent.com/3Alan/images/master/img/%E5%BE%AE%E4%BF%A1%E6%94%AF%E4%BB%98%E5%AE%9D%E4%BA%8C%E5%90%88%E4%B8%80%E6%94%B6%E6%AC%BE%E7%A0%81.jpg" />
