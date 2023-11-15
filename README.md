
# MovieFlix - A Next.js Movie Streaming App

This is a movie streaming application built with Next.js, React, and TypeScript that serves as a clone of popular streaming services like Netflix and Crunchyroll. 

## Features

- Browse movies and shows from various studios including Netflix, Hulu, Disney+, and more
- Search for specific titles 
- View trailers and clips
- Read descriptions, ratings, reviews and more for each title

## Tech Stack

- [Next.js](https://nextjs.org/) - Framework for building server-rendered React apps
- [React](https://reactjs.org/) - Front-end library for building user interfaces
- [TypeScript](https://www.typescriptlang.org/) - Typed superset of JavaScript
- [TMDB API](https://www.themoviedb.org/documentation/api) - Movie metadata API
- [MongoDB](https://www.mongodb.com/) - Document-based NoSQL database

## Live Demo

You can find a live demo of the app deployed on Vercel here:

https://react-movie-application.vercel.app/

## Getting Started

To run the app locally:

```
npm install
npm run dev
```

The app will be served at http://localhost:3000

## API

The app makes use of the TMDB API to fetch movie metadata. You'll need an API key which can be obtained for free from https://www.themoviedb.org/documentation/api

Configure your API key in the `.env` file

## Deployment

The app is deployed and hosted on [Vercel](http://vercel.com). It can be easily deployed with the Vercel CLI.

## Contributing

Pull requests are welcome! Feel free to open an issue or submit PRs for any features and fixes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for more details.
