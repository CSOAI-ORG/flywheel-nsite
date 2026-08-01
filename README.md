# flywheel-nsite — N-site #3 (GitHub Actions, free CPU)

The canonical CSOAI flywheel instrument (`flywheel.py` + `care_battery.py`, embedded
verbatim — same salt `csoai-flywheel-v1`, same split, same judging) running on
GitHub Actions runners: selftest 9/9 first, then a weekly sweep across the
sovereign model set via local Ollama on the runner.

Measurement, not certification. UNMEASURED ≠ fail. Results commit back to
`results/` and mirror to the public dataset huggingface.co/datasets/csoai/csoai-benchmarks.
