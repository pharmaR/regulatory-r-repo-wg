# Architecture

```mermaid
flowchart LR
  pipeline[Risk Assessment Pipeline]
  db[Risk Document Database]
  repo[Package Repository]
  site[Website]

  pipeline -- output --> db
  pipeline -- package --> repo
  db -.-> site
  repo -.-> site
```
