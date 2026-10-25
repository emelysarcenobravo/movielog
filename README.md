# MovieLog

A full-stack movie review app where people sign in, browse movies, and rate and review them. Built by a team of four as the final project for CSC 413 (Software Development) at San Francisco State University, Spring 2026.

> **About this repository:** The source code is kept in a private course repository. This page is a showcase of the project and my contributions. Code is available on request.

![MovieLog dashboard](movielog.jpg)

## My role

Full-stack developer. I owned three features from API to interface:

- **Add a movie** (`POST /movies`): creates a URL-friendly ID from the title and rejects duplicates with a clear error.
- **Search** (`GET /movies/search`): case-insensitive search across title, director, year and genre, returning each movie's average rating and review count.
- **Top rated** (`GET /movies/top-rated`): movies with at least one review and an average of 4 stars or more.
- Built the `/movies` page in Next.js: search bar, add-movie form and top-rated view.

## Tech stack

Java · Spring Boot · MongoDB · Next.js · React · REST APIs · Maven · Git

## Highlights

- The team agreed on one API response shape (`{ status, data, error }`) up front, so front-end and back-end work could happen in parallel.
- Login uses an auth cookie and SHA-256 hashed passwords.

## Links

- [Full case study on my portfolio](https://portfolio-emelysarcenobravo.vercel.app/work/movie-reviews)
- [Final demo](https://drive.google.com/drive/folders/1b0n8cVup9IJNTdFqUi8LKOtWu2Fu6lLR?usp=sharing)
