<h1 align="center">Albert Muratbaev</h1>

<p align="center">
  <strong>Full-stack & Mobile Developer</strong><br>
  Python · Django · FastAPI · TypeScript · React Native · Flutter · React
</p>

<p align="center">
  <a href="./CV.pdf"><img src="https://img.shields.io/badge/CV-Open_PDF-167D85?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="Open CV"></a>
  <a href="mailto:maratbekniyazov@gmail.com"><img src="https://img.shields.io/badge/Email-Contact_Me-334E68?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://www.linkedin.com/in/albert-muratbaev-a39ba4373/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://t.me/albertmra"><img src="https://img.shields.io/badge/Telegram-Message-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"></a>
</p>

I build complete product flows across backend, mobile, web, databases, and infrastructure. My projects focus on secure authorization, reliable state transitions, geospatial features, realtime communication, resilient client behavior, and automated testing.

## What I build

- REST APIs and async services with **Django REST Framework** and **FastAPI**
- Cross-platform mobile applications with **React Native / Expo** and **Flutter / BLoC**
- Web dashboards with **React**, **TypeScript**, **Vite**, and **Leaflet**
- Geospatial search and tracking with **PostgreSQL**, **PostGIS**, maps, GPS, and routing APIs
- Realtime systems with **WebSocket**, **Redis Pub/Sub**, reconnect control, and event validation
- Reproducible local environments with **Docker Compose**, background workers, object storage, and CI checks

## Featured projects

### Real estate marketplace MVP

Production-like educational marketplace with a Django/PostGIS backend and Expo React Native client.

- Versioned `/api/v1` contract, phone/OTP and password authentication, JWT rotation, blacklist, and secure token refresh
- Property and listing domain with constraints, ownership rules, IDOR/BOLA protection, favorites, inquiries, and media
- Bounding-box and radius search, distance ordering, GiST indexes, and presigned S3/MinIO uploads
- Mobile discovery, filters, pagination, localization, resilient loading/error states, and Sentry foundations
- Verified with Docker, Android API 36, **153 passing backend tests**, and **11 mobile unit tests**

### Last-mile delivery platform

Full-stack delivery workflow with Flutter apps, a FastAPI backend, and a React dispatcher dashboard.

- Role-aware client, courier, dispatcher, and admin flows with resource-level authorization
- Order state machine, row locking, audit trail, safe cancellation, and courier assignment
- Authorized WebSocket GPS tracking with validation, throttling, bounded reconnect, and Redis Pub/Sub
- Server-side ETA and route preview through an adapter with timeout, response validation, and fallback
- PostGIS queries, paginated screens, deduplication, Docker Compose, and automated checks across all clients

## Technology map

| Domain | Stack |
| --- | --- |
| Backend | Python, Django, Django REST Framework, FastAPI, Pydantic, SQLAlchemy Async, Alembic |
| Mobile | TypeScript, React Native, Expo, Dart, Flutter, BLoC, Clean Architecture |
| Web | React, TypeScript, Vite, Tailwind CSS, React Leaflet |
| Data & realtime | PostgreSQL, PostGIS, GeoDjango, Redis, WebSocket, Celery |
| Storage & maps | MinIO/S3, Mapbox, OpenStreetMap, OpenRouteService |
| Quality | pytest, pytest-asyncio, Vitest, Flutter tests, Ruff, mypy, ESLint, TypeScript |
| Infrastructure | Docker, Docker Compose, GitHub, CI/CD, Gradle, Android SDK/NDK |

## GitHub overview

<p align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api?username=maratbeknyazov&show_icons=true&hide_border=true&rank_icon=github&theme=transparent&title_color=167D85&icon_color=167D85&text_color=334E68" alt="Albert's GitHub stats">
  <img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=maratbeknyazov&layout=compact&hide_border=true&theme=transparent&title_color=167D85&text_color=334E68&langs_count=8" alt="Albert's most used public repository languages">
</p>

<p align="center">
  <img width="98%" src="https://github-readme-activity-graph.vercel.app/graph?username=maratbeknyazov&bg_color=ffffff&color=334e68&line=167d85&point=102a43&area=true&hide_border=true" alt="Albert's contribution activity graph">
</p>

<p align="center">
  <img width="60%" src="https://streak-stats.demolab.com?user=maratbeknyazov&hide_border=true&background=FFFFFF&ring=167D85&fire=E76F51&currStreakLabel=167D85&sideLabels=334E68&dates=627D98" alt="Albert's GitHub contribution streak">
</p>

<sub>GitHub cards reflect public repository activity, not total professional experience or skill level.</sub>

## Engineering principles

- Server-owned identity and authorization at both role and resource level
- Explicit API contracts, state machines, domain invariants, and database constraints
- Predictable failure handling for network errors, retries, pagination, and realtime reconnects
- Root-cause debugging followed by regression tests
- Honest project scope: locally verified production-like systems, not claimed live production traffic

## Contact

[Email](mailto:maratbekniyazov@gmail.com) · [LinkedIn](https://www.linkedin.com/in/albert-muratbaev-a39ba4373/) · [Telegram](https://t.me/albertmra) · [CV](./CV.pdf)
