# Retry Behavior Under Uncertainty

## Problem
When system feedback is delayed or unclear, users tend to retry actions repeatedly.

## Observations
- Users interpret silence as failure
- Repeated retries increase system load
- Duplicate actions create confusion

## Behavioral Pattern
Uncertainty → Anxiety → Retry → Amplified Failure

## System-Level Impact
- Duplicate requests
- Increased failure probability
- Higher support burden

## Design Implications
- Immediate acknowledgement of actions
- Explicit pending states
- Clear retry guidance

## Conclusion
Clear and timely feedback reduces unnecessary retries and improves user confidence.
