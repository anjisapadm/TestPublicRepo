```mermaid
flowchart TD
    A[Start] --> B{Is it sunny?}
    B -->|Yes| C[Go outside]
    B -->|No| D[Stay inside]
    C --> E[Enjoy the sun!]
    D --> F[Find something fun to do indoors]
    E --> G[End]
    F --> G[End]
