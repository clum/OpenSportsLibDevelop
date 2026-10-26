# Project Notes

## OpenSportsLib

- Documentation: <https://opensportslab.github.io/opensportslib/>
- Getting started: <https://opensportslab.github.io/opensportslib/getting-started/>
- OpenSportsLib is a Python library for sports-video experiments, including classification, localization/action spotting, and visual question answering.
- The library does not include a ready-to-run dataset; workflows need video files and OSL JSON manifests.

## Python Environment

- Conda environment name: `osl`
- Python version: 3.12 or newer (per the installation guide)

Create and activate the environment:

```bash
conda create -n osl python=3.12 pip
conda activate osl
```

Install OpenSportsLib and its base dependencies:

```bash
python -m pip install --upgrade pip
pip install opensportslib
opensportslib setup
```

`opensportslib setup` installs the appropriate PyTorch profile for the machine and replaces the installed Torch stack. Keep this in the dedicated environment.

## Data and Configuration

- Starter classification config: `opensportslib/configs/classification/video.yaml` (available after installing the package).
- Dataset splits are OSL JSON manifests, typically `train.json`, `valid.json`, and `test.json`.
- Record project-specific dataset locations, labels, and config overrides here:

  - Data root:
  - Train manifest:
  - Validation manifest:
  - Test manifest:
  - Config used:

## Experiments and Commands

Use this section to record commands, checkpoints, prediction outputs, and evaluation results.

| Date | Task / config | Dataset or split | Checkpoint / output | Notes |
|---|---|---|---|---|
| | | | | |


## Research Notes

This details some notes to myself.

### 10/25/26
- You need to run commands in the Anaconda Prompt (normal terminal or PowerShell may not have access to the activated environment).

## Questions and Follow-ups

- [ ] Add the dataset and manifest locations when known.
- [ ] Record the first example run and any setup issues.
