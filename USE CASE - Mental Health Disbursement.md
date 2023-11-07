```mermaid
sequenceDiagram
  participant Community
  participant Donor
  participant HRVEST
  participant NonProfit
  participant CounselingService
  
  Community->>HRVEST: Identifies Need for Mental Health Support
  rect rgb(213, 246, 255)
    Donor->>HRVEST: Donates Funds
    HRVEST->>NonProfit: Transfers Funds
    HRVEST->>Donor: Provides Real-Time Monitoring
  end
  NonProfit->>CounselingService: Provides Counseling
  rect rgb(213, 246, 255)
    CounselingService->>HRVEST: Confirms Service Delivery
    HRVEST->>Community: Provides Real-Time Impact Analysis
  end
```
