# FutbolData frontend

This repository contains only the static frontend published with GitHub Pages. The backend is hosted separately.

The Pages workflow reads the repository variable `API_BASE_URL` and uses it as the HTTPS base URL for `/api/*` and EventSource requests. Set it in the repository's **Settings → Secrets and variables → Actions → Variables**. Until it points to a publicly reachable HTTPS backend, the site shell can load but live backend data will not connect.
