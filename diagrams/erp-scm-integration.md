# ERP and SAP SCM/APO Integration Flow

```mermaid
flowchart LR
    E[SAP ERP] -->|Materials, BOMs, Routings, Work Centers, Stocks| C[CIF Integration]
    C --> A[SAP SCM / APO]
    A --> S[SNP Supply Planning]
    S --> P[PP/DS Detailed Scheduling]
    P --> C
    C -->|Approved planning results / synchronization| E
```

The diagram shows the conceptual information flow used in the Week 3 project. CIF is treated as the synchronization layer between ERP execution data and APO planning objects.
