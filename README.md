# Filmoflix Route Tree Documentation

This document explains the routing structure and organization of the **Filmoflix** platform. The purpose of this structure is to provide a clear and easy-to-navigate system for accessing the various pages of the website.

---

## Metadata

- **Update Time**: `2024-11-29`
  - This indicates the last time the routing metadata was updated.

---

## Base Information

- **Protocol**: `https`
- **Base URL**: `www.filmoflix.is`

The website operates under a secure HTTPS protocol and is accessible via the given base URL.

---

## Route Tree

### Films

The `films` section provides access to the movies available on Filmoflix. 

| **Key**      | **Path**            | **Description**                                     |
|--------------|---------------------|-----------------------------------------------------|
| `this`       | `/filmstreaming`    | The main page for browsing and streaming films.    |
| `gender`     | `/filmstreaming/genre` | Access films filtered by genre.                   |

### Series

The `series` section allows users to browse and stream TV series.

| **Key**      | **Path**              | **Description**                                     |
|--------------|-----------------------|-----------------------------------------------------|
| `this`       | `/seriestreaming`     | The main page for browsing and streaming series.    |
| `gender`     | `/seriestreaming/genre` | Access series filtered by genre.                   |

### Search

The `search` section lets users perform keyword-based searches.

| **Key**      | **Path**        | **Description**                  |
|--------------|-----------------|----------------------------------|
| `this`       | `/search`       | Access the global search feature.|

---

---

## Example Usage

### Accessing Movies
- **Films Home**: `https://www.filmoflix.is/filmstreaming`
- **Films by Genre**: `https://www.filmoflix.is/filmstreaming/genre`

### Accessing Series
- **Series Home**: `https://www.filmoflix.is/seriestreaming`
- **Series by Genre**: `https://www.filmoflix.is/seriestreaming/genre`

### Using Search
- **Search Page**: `https://www.filmoflix.is/search`

---

Feel free to use this structure to build or navigate the **Filmoflix** platform efficiently!
