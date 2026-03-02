graph TD
    subgraph S1 [Step 1: Data Gathering]
        A1[<b>Database Update</b><br/>Data Unit - XML DB]
        A2[<b>Soft Data Update</b><br/>Analyst - Screening Report]
        A3[<b>Global Projections</b><br/>GP Team - Matlab Files]
    end

    subgraph S2 [Step 2: Analysis]
        B[<b>Country Presentation</b><br/>Analyst - Macro Analysis]
    end

    subgraph S3 [Step 3: Modeling & Discussion]
        C[<b>Forecasting & Assumptions</b><br/>Senior, Analyst & Model Operator]
    end

    subgraph S4 [Step 4: Finalization]
        D[<b>Drafting Report</b><br/>Analyst & Model Operator]
    end

    subgraph S5 [Step 5: Review & Delivery]
        E1[<b>External Review</b><br/>Senior Economist]
        E2[<b>English Editing</b><br/>Language Proofreading]
        E3[<b>Final Replication</b><br/>Model Operator - 2+ Machines]
        F[<b>Publication</b><br/>SVN Commit & Archive]
    end

    S1 --> S2
    S2 --> S3
    S3 --> S4
    S4 --> S5

    style S2 fill:#f0f7ff,stroke:#005fb8,stroke-width:2px
    style S4 fill:#f0f7ff,stroke:#005fb8,stroke-width:2px