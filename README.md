This project studies how groups of LLM agents behave when they repeatedly interact.

It investigates how five main factors affect collective stability:

Population size (N)
Memory (M)
Temperature/stochasticity (T)
Adaptation rate (α)
Interaction frequency (F)
The goal is to discover whether LLM societies become stable, adaptive, oscillatory, polarized, or unstable, and whether there are measurable stability/phase boundaries between these regimes.

The project uses games such as the Prisoner’s Dilemma, Stag Hunt, Battle of the Sexes, and Public Goods Game, combined with different network structures and controlled perturbations.



PIPELINE



Initialize population

        ↓
Initialize network
        ↓

Set N, M, T, α, F, G, H

        ↓

Run repeated interactions
        ↓

Generate LLM actions
        ↓

Compute rewards
        ↓

Update memory
        ↓

Apply adaptation
        ↓

Log trajectories
        ↓

Apply perturbations
        ↓

Compute observables
      ↓

Classify dynamical regime
        ↓

Estimate stability frontier








Project Status
Status: Research / Experimental Framework

The proposed stability frontier and phase transitions are hypotheses to be tested, not established empirical results.

Future work includes:

Implementing the complete simulation engine
Connecting multiple LLM providers/models
Running parameter sweeps
Replicating experiments across seeds
Measuring finite-size effects
Comparing network topologies
Testing multiple games
Estimating empirical stability surfaces
Testing generalization across LLM family
