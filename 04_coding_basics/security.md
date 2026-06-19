## Important Security Rule

Do not put API keys directly into code.

Bad:

```js
const apiKey = "sk-or-123456";
```

Better:

```js
const apiKey = process.env.OPENROUTER_API_KEY;
```

Use a `.env` file locally.

---