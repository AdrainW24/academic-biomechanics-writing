# Biomechanics Methods Checklist

Use this checklist before polishing any methods, results, or discussion text.

## Participants

- Report sample size, sex distribution, age, height, mass, sport/training level, limb dominance, injury history, and inclusion/exclusion criteria.
- Clarify whether the design is cross-sectional, repeated-measures, longitudinal, intervention, reliability, or validation.
- Flag underpowered group comparisons, missing effect sizes, and lack of justification for sample size.

## Tasks And Protocol

- Specify the task: gait, running, cutting, landing, jumping, fatigue, balance, sport-specific skill, or rehabilitation task.
- Report speed, slope, surface, footwear, landing height, jump target, fatigue criteria, warm-up, familiarization, trial count, rest intervals, and valid-trial criteria.
- Check whether the task is ecologically valid enough for the claims being made.

## Instrumentation

- Motion capture: system, camera count, sampling rate, marker set, calibration, gap filling, and coordinate system.
- Force plates: sampling rate, threshold, filtering, synchronization, and definition of stance/contact events.
- EMG: muscles, placement standard, sampling rate, filtering, rectification, normalization, onset detection, and crosstalk concerns.
- IMU/wearables: sensor model, placement, sampling rate, calibration, drift correction, fusion algorithm, and validation against reference systems.

## Processing

- Report filter type, cutoff frequency, order, bidirectional filtering, and rationale.
- Define joint centers, segment coordinate systems, joint angle sequence, and sign conventions.
- State normalization choices: body mass, height, leg length, stance time, gait cycle, MVC, peak dynamic value, or baseline.
- For inverse dynamics, state assumptions, external loads, segment inertial parameters, and event definitions.

## Modeling

- For OpenSim or musculoskeletal modeling, report model name, scaling process, marker weights, inverse kinematics residuals, inverse dynamics settings, muscle analysis/static optimization choices, and validation checks.
- Flag claims about muscle force, joint loading, or injury mechanism when model assumptions are not sufficiently described.

## Variables

- Align dependent variables with hypotheses.
- Common variables: joint angles, moments, powers, ground reaction forces, loading rate, center of pressure, symmetry indices, coordination, variability, EMG amplitude/timing, muscle forces, and joint contact forces.
- Avoid reporting many variables without a hierarchy; separate primary, secondary, and exploratory outcomes.

## Statistics

- Match analysis to the design: paired tests, repeated-measures ANOVA, linear mixed models, regression, SPM, reliability statistics, or validation metrics.
- Report effect sizes, confidence intervals, assumptions, missing-data handling, and multiple-comparison control.
- For reliability: ICC model, SEM, MDC, CV, Bland-Altman limits, and test-retest interval.
- For machine learning: train/test split, cross-validation, leakage prevention, external validation, and clinically meaningful metrics.

## Interpretation

- Cross-sectional designs cannot establish causality.
- Acute lab tasks should not be overstated as long-term injury prevention or performance enhancement.
- Statistical significance is not automatically practical, clinical, or performance significance.
- Discuss measurement error, task constraints, sample specificity, and model assumptions.
