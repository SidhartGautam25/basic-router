# basic-tiny-router

A lightweight and expressive routing library for Node.js designed to work without external frameworks. Inspired by popular routers but tailored for simplicity, performance, and full control.

## Features

- ✅ Supports all major HTTP methods: `GET`, `POST`, `PUT`, `DELETE`, `OPTIONS`, `HEAD`
- 🧩 Middleware-style `.use()` support
- 🔑 Dynamic route parameters (`/users/:id`)
- ⚡ Fast route matching using [`regexparam`](https://www.npmjs.com/package/regexparam)
- 📐 Routes sorted by method priority for predictable behavior

---

## Installation

```bash
npm i basic-tiny-router
```
