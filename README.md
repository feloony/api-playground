# ◈ API Playground

A fast, beautiful browser-based REST API client for developers. Build requests, inspect responses, and debug endpoints without a bloated setup.

## ✨ Features

- GET, POST, PUT, PATCH, DELETE and HEAD requests
- Query parameter builder
- Custom request headers
- JSON request body editor
- Live status, timing and response-size information
- Pretty-printed JSON responses
- Raw response viewer
- Response headers viewer
- One-click response copying
- Quick example endpoints
- Responsive dark UI
- No account required
- Static frontend with no application backend

## 🚀 Getting started

```bash
git clone https://github.com/feloony/api-playground.git
cd api-playground
```

Then open `index.html` in a browser or serve the directory with any static web server.

## 🌐 Browser requests & CORS

API Playground uses the browser Fetch API, so the target API needs to allow cross-origin browser requests through CORS. APIs that block browser access will require a server-side proxy.

## 🔒 Privacy

The application is designed to be local-first. It does not require an account or built-in request database. Do not paste production secrets into requests you do not trust.

## 🛠️ Tech

- HTML
- CSS
- Vanilla JavaScript
- Fetch API

No build step or framework dependency is required.

## 🤝 Contributing

Fork the repository, create a feature branch, test your changes in a modern browser, and open a pull request. Ideas include request collections, environments, authentication helpers, cURL import/export, GraphQL support, keyboard shortcuts, and optional local persistence.

## 📄 License

MIT License