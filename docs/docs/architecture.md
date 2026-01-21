#### Architecture Overview

PulseFlow follows a hybrid architecture:

- Batch ETL handles large-scale historical data and heavy aggregations
- Streaming pipelines handle near-real-time updates
- SQL engines are used as the primary computation layer
- Application code focuses on orchestration and correctness

This separation ensures predictable performance and easier debugging.

