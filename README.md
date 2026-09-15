# Process Plant Debottlenecking & Capacity Expansion Using Aspen Plus

## Overview

An Aspen Plus V14 process simulation study evaluating capacity
expansion and reflux-based debottlenecking of a binary
benzene–toluene distillation system.

## Project Objectives

- Develop and converge a RadFrac distillation model
- Establish a 1000 kg/h base case
- Evaluate 20% and 30% capacity expansion
- Analyze material and energy requirements
- Evaluate reflux-ratio adjustment as a debottlenecking strategy
- Quantify separation and utility trade-offs

## Process Model

| Parameter | Value |
|---|---|
| Software | Aspen Plus V14 |
| Column | RadFrac |
| Equilibrium stages | 20 |
| Condenser | Total |
| Reboiler | Kettle |
| Feed | 50 mol% Benzene + 50 mol% Toluene |
| Feed pressure | 1.5 bar |
| Feed temperature | 25 °C |
| Base reflux ratio | 2.50 |
| Debottlenecked reflux ratio | 2.75 |

## Simulation Cases

| Case | Feed | Distillate | Reflux Ratio |
|---|---:|---:|---:|
| Base | 1000 kg/h | 500 kg/h | 2.50 |
| 20% Expansion | 1200 kg/h | 600 kg/h | 2.50 |
| 30% Expansion | 1300 kg/h | 650 kg/h | 2.50 |
| Debottlenecked | 1300 kg/h | 650 kg/h | 2.75 |

## Key Results

The 30% expansion increased feed throughput from 1000 to
1300 kg/h while maintaining essentially the same separation
behavior under the original operating conditions.

At 1300 kg/h, increasing the reflux ratio from 2.50 to 2.75:

- Reduced benzene loss to bottoms from approximately 0.0984%
  to 0.0771%
- Improved benzene recovery to approximately 99.923%
- Increased condenser duty from 245.52 to 263.06 kW
- Increased reboiler duty from 262.21 to 279.75 kW

## Engineering Insight

The study demonstrates the trade-off between separation
performance and thermal utility consumption during capacity
expansion.

The reflux adjustment is treated as an evaluated operating
debottlenecking strategy. No physical flooding or equipment
capacity constraint is claimed because hydraulic internals and
site-specific equipment limits were outside the scope of the model.

## Repository Contents

- `Aspen_Files/` — Aspen Plus simulation cases
- `Report/` — Final project report
- `Figures/` — Simulation plots and results
- `Results/` — Consolidated numerical results

## Tools & Skills

- Aspen Plus V14
- RadFrac
- Distillation
- Process Simulation
- Material & Energy Balance
- Capacity Expansion
- Debottlenecking
- Utility Analysis
