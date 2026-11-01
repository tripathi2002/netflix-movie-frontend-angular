# Netflix Movie Frontend (Angular)

Angular frontend for a Netflix-style movie app, intended to pair with [netflix-movie-api](https://github.com/tripathi2002/netflix-movie-api). It currently implements a Netflix-inspired login page and the shared header layout, with a custom SCSS design system.

## Features

- Login page with password show/hide toggle
- Header layout component
- Custom SCSS architecture: variables, grid, mixins, buttons, forms, hero section, cookie bar, media queries
- Manrope web fonts
- Docker dev setup (`Dockerfile.dev`, `docker-compose.dev.yml`)

## Tech stack

Angular 20 (standalone components) · TypeScript · SCSS · RxJS · Docker

## Project structure

```
src/app/app.routes.ts               # '' → /login
src/app/components/layouts/header/
src/app/components/pages/login.component/
src/environments/environment.ts
src/sass/                           # partials, mixins, grid, utils
src/fonts/                          # Manrope
public/                             # logo, login background, icons
```

## Getting started

```bash
npm install
npm start                 # http://localhost:4200
npm run start:dev         # development configuration
npm run build
```

With Docker:

```bash
docker compose -f docker-compose.dev.yml up
```

## Environment variables

None. Configuration lives in `src/environments/environment.ts`.
## Screenshots

_Screenshots coming soon._

## License

No license file has been added to this repository yet.
