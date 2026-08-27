# Awesome Formboost

A curated collection of official examples, starter templates, integrations, tutorials, and community resources for [Formboost](https://formboost.app/).

Formboost is a developer-first form backend for websites. Send form submissions to:

```text
https://formboost.app/f/YOUR_ENDPOINT
```

## Official resources

- [Formboost](https://formboost.app/)
- [Documentation](https://formboost.app/docs)
- [Formboost Docs on GitHub](https://github.com/formboost/formboost-docs)
- [All-in-one Examples](https://github.com/formboost/formboost-examples)

## Framework examples

- [HTML Examples](https://github.com/formboost/formboost-html-examples) — contact, newsletter, feedback, and survey forms
- [React Examples](https://github.com/formboost/formboost-react-examples) — React + Vite with fetch and Axios
- [Next.js Examples](https://github.com/formboost/formboost-nextjs-examples) — App Router client and server-action patterns

## Starter templates

- [Formboost Starter Templates](https://github.com/formboost/formboost-starter-templates) — ready-to-clone contact, newsletter, and feedback forms

## Integrations

Formboost supports integrations and workflow patterns including:

- Slack
- Discord
- Telegram
- HTTP webhooks
- Zapier
- n8n
- Google Sheets

See the [Formboost integrations documentation](https://formboost.app/docs/integrations) for current setup guides.

## Useful patterns

### Plain HTML

```html
<form action="https://formboost.app/f/YOUR_ENDPOINT" method="POST">
  <input name="email" type="email" required />
  <button type="submit">Submit</button>
</form>
```

### JavaScript

```js
await fetch("https://formboost.app/f/YOUR_ENDPOINT", {
  method: "POST",
  headers: { "Content-Type": "application/json" },
  body: JSON.stringify({
    name: "Alex Johnson",
    email: "alex@example.com",
    message: "Hello from Formboost"
  })
});
```

## Contributing

Have a useful Formboost example, integration, tutorial, or starter? Open a pull request and add it to the relevant section.

Please prefer resources that are genuinely useful to developers and link to the canonical [Formboost website](https://formboost.app/) or [documentation](https://formboost.app/docs) where appropriate.
