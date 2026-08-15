# Mininet / Open vSwitch Validation

This directory contains the high-fidelity network validation experiments
for IDCLM using Mininet and Open vSwitch.

## Objectives

The experiments will evaluate:

- Actual enforcement-state drift
- Detection of unauthorized configuration changes
- Rollback and restoration
- Replay/freshness protection
- Partial deployment inconsistency
- Multi-device drift
- Detection and recovery latency
- Resource overhead
- Scalability

## Planned experiment scales

- 10 virtual enforcement points
- 50 virtual enforcement points
- 100 virtual enforcement points
- 500 virtual enforcement points
- 1,000 virtual enforcement points

## Evidence rule

Results must be generated from actual experimental runs. No simulated
or placeholder results will be reported as Mininet/Open vSwitch evidence.
