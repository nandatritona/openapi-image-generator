# OpenAI Image Generator

This is a simple image generator built with Node.js and Express that uses [OpenAI's Dall-E models](https://beta.openai.com/docs/guides/images) to generate images.

![Screenshot 2023-04-18 143424](https://user-images.githubusercontent.com/75880817/232705226-b546d357-93da-4c28-8783-9cbbf80929ca.png)


## Usage

Rename the `example.env` file to `.env`.

Generate an API KEY at [OpenAI](https://beta.openai.com/) and add it to the `.env` file.

Install the dependencies

```bash
npm install
```

Run server

```bash
npm start
```

Visit `http://localhost:5001` in your browser.

The endpoint is at `POST http://localhost:5001/openai/generateimage`.
