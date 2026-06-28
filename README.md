# Algorithmic Energy Optimization Framework for Tiered Storage Architectures

A conceptual Python prototype demonstrating a 69.60% reduction in data center storage subsystem energy consumption through intelligent, predictive traffic pacing.

## Architectural Mechanism
Traditional storage arrays react blindly to individual retrieval requests. When automated scripts, search indexers, or background system tasks sweep through cold storage tiers, they trigger continuous mechanical drive wake-ups. This inflicts severe electrical inrush current demands and volatile cooling load shocks on the facility.

This framework mitigates device-level physical strain by intercepting traffic prior to hardware instruction processing via three pipeline stages:
1. **Cold Data AI Gatekeeper:** A lightweight metadata token-classifier that distinguishes human user requests from automated background maintenance routines.
2. **Pre-Wake Verification Firewall:** An interception layer that transparently buffers non-urgent bot traffic, keeping cold media platters at a resting low-power state.
3. **Consumer Diversity Coefficient Scheduler:** An algebraic batching algorithm that aggregates deferred traffic, spinning hardware up exactly once to flush the entire queued workload sequence smoothly.

## Simulation Data Output
Below is the empirical trajectory tracking cumulative energy draw (Joules) across a standard mixed-workload traffic profile:

![Energy Profile Chart](energy_profile_chart.png)

## How to Run the Prototype Locally
Ensure you have Python 3 and Matplotlib installed, then clone and execute:
```bash
git clone [https://github.com/VishalInc/green-computing-prototype.git](https://github.com/VishalInc/green-computing-prototype.git)
cd green-computing-prototype
python simulation.py
