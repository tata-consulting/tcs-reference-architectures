# Platform system context

```mermaid
flowchart LR
    Developers[Product teams] --> Portal[Developer portal]
    Portal --> Templates[Golden path templates]
    Portal --> Catalog[Software catalog]
    Templates --> CI[CI pipeline]
    CI --> GitOps[GitOps delivery]
    GitOps --> Runtime[Kubernetes runtime]
    Runtime --> Observability[Observability platform]
    Runtime --> Policies[Policy guardrails]
    PlatformTeam[Platform team] --> Portal
    PlatformTeam --> Policies
    Security[Security and compliance] --> Policies
    Leadership[Delivery leadership] --> Scorecards[Adoption scorecards]
    Observability --> Scorecards
    Catalog --> Scorecards
```

This diagram captures the default consulting narrative: product teams enter through the portal, delivery is standardized through templates and GitOps, and operating signals roll up to scorecards.
