# <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original.svg" height="24"> Express.js Template

Minimal Express.js API server with routing, middleware, and static file support.

## Local Development

Install dependencies:
```bash
npm install
```

Start the server:
```bash
npm start
```

Server runs on http://localhost:3000

## File Structure

```
├── app.js              # Express app setup
├── bin/www             # Server entry point
├── routes/
│   ├── index.js        # Home route
│   └── users.js        # Users route
├── public/             # Static files
├── Dockerfile          # Container build
└── package.json
```

---

## <img src="https://github.com/sugasrc.png" height="20"> Deploying with Suga

1. Click **Use this template** to create your own repository

2. Push changes - GitHub Actions builds and pushes to GHCR automatically

3. In the Suga dashboard, update the **Image URI** for your service:
   ```
   ghcr.io/YOUR_USERNAME/YOUR_REPO:latest
   ```

4. Ensure your GHCR package is public
