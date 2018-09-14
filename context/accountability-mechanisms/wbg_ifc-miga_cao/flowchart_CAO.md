## CAO Complaints Mechanism<br>&mdash;Flowchart of the complaints handling process


```mermaid
graph TD
 A>Complaint] --> B{Eligible for<br /> assessment?}
          subgraph
 B -->|No| C(Case closed)
 B -->|Yes| D[Assessment]
 D --> E{Decision for <br/>Dispute Resolution<br/> or Compliance?}
          end
          subgraph
 E -->|Dispute Resolution| F[Facilitate dispute resolution process]
 F --> H{Agreement reached?}
 H -->|Yes| I[Monitoring]
 I --> J{Agreement<br/> implemented?}
            end
            J -->|No| K
            H -->|No| K[Transfer case]
            K --> G
           subgraph
 E -->|Compliance| G[Appraisal]
  G --> L{Merits an investigation?}
 L -->|Yes| N[Conduct investigation]
 N --> O[Monitoring]
 O --> P{Compliance<br/> reached?}
 P -->|No| O
           end
 J -->|Yes| Q
  L -->|No| Q
 P -->|Yes| Q(Case closed)

 style A fill:#ccc
 style B fill:#f9e79f,stroke:#ffc300
 style C fill:#ccc
 style D fill:#f9e79f,stroke:#ffc300,stroke-width:2px
 style E fill:#f9e79f,stroke:#ffc300
 style F fill:#d5f5e3
 style G fill:#d6eaf8
 style H fill:#d5f5e3,stroke:#76d7c4,stroke-width:2px
 style I fill:#d5f5e3
 style J fill:#d5f5e3,stroke:#76d7c4,stroke-width:2px
 style K fill:#ccc
 style L fill:#d6eaf8
 style N fill:#d6eaf8
 style O fill:#d6eaf8
 style P fill:#d6eaf8
 style Q fill:#ccc
```
