# layer4-temporal-patterns

This repository contains spike-sorted single unit recordings from Layer 4 neurons in rat barrel cortex responding to various whisker stimuli.

## Data Organization

The data consists of CSV files containing spike-sorted neural responses, where:
- Each file (e.g., `6042062.csv`) represents a recording session from a specific stimulus type
- Each column represents the response to a different stimulus amplitude/velocity
- Each row represents a timepoint (in milliseconds)
- Values indicate the neural response at that timepoint corrected for spontaneous activity

### Data Format
- Sampling rate: 1ms bins
- File format: CSV (comma-separated values)
- Column headers: `{cell number}{amplitude}`
  - e.g., `f01_stimulus_1`, `f01_stimulus_2`, etc. represent different stimulus amplitudes

### Stimulus Parameters
- Basic stimulus: 5 velocities (30, 60, 150, 250, 400 mm/sec)
- Contact, Rough, Smooth, Whisking stimuli: 10 amplitudes (0.2mm to 3.6mm in 0.4mm steps)