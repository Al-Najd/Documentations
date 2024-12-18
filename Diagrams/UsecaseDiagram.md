```mermaid
graph TD
    User((User)) -->|Logs In| App[Al Najd App]
    User -->|Logs Daily Prayer| App
    User -->|Logs Good Deed| App
    User -->|Views Weekly Overview| App
    App -->|Authenticates| Backend[(Backend Server)]
    App -->|Stores Data| Database[(Database)]
    App -->|Retrieves Achievements| Database
    App -->|Displays Achievements| User
```