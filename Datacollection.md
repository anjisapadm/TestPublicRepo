```mermaid
graph TD;
    A[Start] --> B{Is it working?};
    B -->|Yes| C[Keep it up!];
    B -->|No| D[Debug the issue with a very long description that needs more space to display properly];
    D --> E{Issue fixed?};
    E -->|Yes| C;
    E -->|No| D;
    C --> F[End];
