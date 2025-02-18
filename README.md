```mermaid
graph TD;
    A[Start] --> B[Customer books a service with detailed data];
    B --> C[Admin generates a proforma invoice];
    C --> D[Customer confirms or cancels the booking];
    D -->|Confirmed| E[Admin assigns a mechanic to the job];
    D -->|Cancelled| F[Process finishes];
    E --> G[Proceed to payment];
    G --> H[Mechanic performs the work];
    H --> I[Customer rates and provides feedback];
    I --> J[Process finishes];
