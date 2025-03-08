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

| Field            | Description            |
|------------------|------------------------|
| **ID**           | Unique song identifier |
| **Name**         | Song title             |
| **Duration**     | Song length (in ms)    |
| **Spotify Link** | Listen on Spotify      |
| **Play Count**   | Number of times played |
| **Popularity**   | Popularity score       |
| **Played At**    | Last played timestamp  |

### Artist Data

| Field            | Description                        |
|------------------|------------------------------------|
| **ID**           | Unique artist identifier           |
| **Name**         | Artist's name                      |
| **Type**         | Artist category (e.g., solo, band) |
| **Spotify Link** | View on Spotify                    |
