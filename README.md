# HTTP Status Dogs 🐶📶

[![Sponsored by Stackaura](https://img.shields.io/badge/Sponsored_by-Stackaura-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://www.stackaura.com/)
[![Dogs](https://img.shields.io/badge/HTTP_Status-Dogs-orange.svg?style=for-the-badge)](https://www.stackaura.com/)

A delightful, easy-to-use API and visual reference guide that maps every standard HTTP status code to a corresponding image of a dog. Because debugging network errors should make you smile.

---

<div align="center">
  <h3>Sponsored by <a href="https://www.stackaura.com/">Stackaura</a></h3>
  <p>Helping developers build better websites and applications through powerful automation and design.</p>
  <a href="https://www.stackaura.com/"><img src="https://img.shields.io/badge/Visit_Stackaura-Black?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Visit Stackaura" /></a>
</div>

---

## 🦴 What is HTTP Status Dogs?

Ever stared at a `418 I'm a teapot` or a `406 Not Acceptable` error and wished it was cuter? This project provides a programmatic way to return high-quality images of dogs matching the semantic meaning (or at least the humor) of various HTTP status codes.

Perfect for custom error pages, easter eggs, or just learning HTTP statuses in a fun way!

## 🚀 Quick Usage

It's as simple as an image tag or a curl request!

**Using an Image Tag:**
```html
<img src="https://httpstatusdogs.com/img/404.jpg" alt="404 Not Found Dog">
```

**Using the API (JSON Response):**
```bash
curl https://api.httpstatusdogs.com/status/404
```

**JSON Response:**
```json
{
  "code": 404,
  "status_text": "Not Found",
  "dog_url": "https://httpstatusdogs.com/img/404.jpg"
}
```

## 📚 The Code Categories

The dogs are grouped by the standard HTTP response classes:

- **1xx (Informational):** The dog is listening, waiting, or fetching the stick.
- **2xx (Success):** Happy dogs! Good boys getting treats. `200 OK`.
- **3xx (Redirection):** Dogs chasing their tails or running in the wrong direction.
- **4xx (Client Error):** The dog ate your homework (`400 Bad Request`), or is hiding (`404 Not Found`).
- **5xx (Server Error):** Chaos. Dogs tangled in their leashes, or napping on the keyboard (`500 Internal Server Error`).

## 🛠️ Self-Hosting

Want to host your own pack of HTTP dogs?

```bash
git clone https://github.com/RanaAhmar/http-status-dogs.git
cd http-status-dogs
npm install
npm start
```
By default, the server runs on `http://localhost:3000`.

## 🤝 Contributing

Did we miss a status code? Found a dog that perfectly represents `403 Forbidden`? We'd love your help!
1. Fork the repo.
2. Add your image to `/public/img/`.
3. Update `codes.json` with the new status and attribution.
4. Submit a Pull Request!

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
*Maintained with ❤️ by [Stackaura](https://www.stackaura.com/). Fetch!*


---

## 🚀 Discover More from Stackaura

If you found this tool useful, check out our other high-performance web utilities and follow **Ahmar Hussain** for more open-source excellence.

### 🌟 Featured Projects
- **[Free LLM APIs](https://github.com/RanaAhmar/free-llm-apis)** - A curated list of zero-cost AI endpoints.
- **[Awesome MCP Servers](https://github.com/RanaAhmar/awesome-mcp-servers)** - The ultimate collection of Model Context Protocol implementations.
- **[System Design Cheatsheet](https://github.com/RanaAhmar/system-design-cheatsheet)** - Master complex architectures in minutes.
- **[Next.js SaaS Starter](https://github.com/RanaAhmar/nextjs-saas-starter)** - The fastest way to launch your next product.

### 🔗 Stay Connected
- **Website:** [stackaura.com](https://www.stackaura.com/)
- **Author:** [Ahmar Hussain](https://github.com/RanaAhmar)

---
