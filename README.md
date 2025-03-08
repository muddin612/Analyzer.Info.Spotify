# Music Data API

## Overview

This project manages user and music-related data, including user details, song information, and artist metadata. The data is sourced from Spotify and includes play history, popularity metrics, and other key attributes.

## Data Structure

### User Data

| Field            | Description            |
|------------------|------------------------|
| **Display Name** | User's display name    |
| **Email**        | User's email address   |
| **Country**      | User's country         |
| **ID**           | Unique user identifier |
| **First Name**   | User's first name      |
| **Last Name**    | User's last name       |

### Song Data

| Field            | Description            | Data Type |
|------------------|------------------------|-----------|
| **ID**           | Unique song identifier | String    |
| **Name**         | Song title             | String    |
| **Duration**     | Song length (in ms)    | float     |
| **Spotify Link** | Listen on Spotify      | String    |
| **Play Count**   | Number of times played | ArrayList |
| **Popularity**   | Popularity score       | int       |
| **Played At**    | Last played timestamp  | ArrayList |

### Artist Data

| Field            | Description                        |
|------------------|------------------------------------|
| **ID**           | Unique artist identifier           |
| **Name**         | Artist's name                      |
| **Type**         | Artist category (e.g., solo, band) |
| **Spotify Link** | View on Spotify                    |

