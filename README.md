# ⚡ REACT RADAR ⚡

Desktop Radar Application powered by the [National Weather Service API](https://www.weather.gov/documentation/services-web-api).

## Features

- Progressive Web Application (PWA) that you can install on your computer. (Could probably do this with [Vite PWA](https://vite-pwa-org.netlify.app/) Plugin)
- Desktop Notifications for severe weather alerts
  - [Serivce Worker API](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API)
    - [NotificationEvent](https://developer.mozilla.org/en-US/docs/Web/API/NotificationEvent)
- [React Leaflet](https://react-leaflet.js.org/) with [OpenStreetMap](https://www.openstreetmap.org/)
- [Vite](https://vitejs.dev/) and [Vitest](https://vitest.dev/)
- [ESLint](https://eslint.org/) and [Prettier](https://prettier.io/)
- [GraphQL](https://graphql.org/)

## Near Goals (TODO List)

- [ ] **[GeoJSON](https://geojson.org/) support** - It probably has this already, but let's make sure
- [ ] **RESTful API converted to GraphQL with [`apollo-rest-link`](https://www.apollographql.com/docs/react/api/link/apollo-link-rest/)** - The NWS Weather API is RESTful, but it might be possible to migrate it to GraphQL
- [ ] **KML file import support** - Important! Map files are in KML format.
  - [ ] Radar
  - [ ] Severe Weather Polygons
- [ ] **Mobile App** - There's a tutorial for it...sort of. [This guy does it with Vue and Ionic.](https://dev.to/aaronksaunders/how-to-create-a-mobile-app-using-vite-vue-and-ionic-capacitor-in-8-minutes-including-explanation-1c4g) Need to find something for React.

## Stretch Goals / Future features (Wish List)

- Lightning detection (Either through [Blitzortung](https://map.blitzortung.org/) or [GHRC](https://ghrc.nsstc.nasa.gov/lightning/))