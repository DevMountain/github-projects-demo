# Database Schema

```mermaid
erDiagram
    MOVIE ||--o{ RATING : contains
    USER ||--o{ RATING : creates
    MOVIE {
        int id
        string title
    }
```
