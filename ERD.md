# Taylor Swift - The Myth, the Legend

Quantitative and qualitative statistics of Taylor Swift's songs

```mermaid
---
title: TSwiftDB

---
erDiagram
    t[adgemllc_fvvqu_tracks]
        string id
        string album_id
        string album_name
        string track_name
        date release_date
        string duration
        int track_number
        int popularity
        bool explicit
        string uri
    f[adgemllc_fvvqu_features]
        string id
        string album_id
        string album_name
        string track_name
        float danceability
        float energy
        int key_
        float loudness
        int mode
        float speechiness
        float acousticness
        float instrumentalness
        float liveness
        float valence
        float tempo
    t ||--|| has
```
