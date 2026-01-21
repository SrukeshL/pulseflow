# Failure Model

PulseFlow explicitly documents failure scenarios, including:

- Database slowdown causing streaming backpressure
- Consumer restarts and offset recovery
- Partial batch ETL failures
- Data duplication under at-least-once semantics

Each failure scenario includes:
- Detection highlight
- Impact radius
- Recovery strategy
