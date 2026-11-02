# geoskill-debris-flow-risk

> Identify potential debris-flow gullies, integrate terrain, material source, rainfall trigger, and downstream exposure to produce basin-level hazard screening and risk assessment.

See [SKILL.md](SKILL.md) for full usage, inputs and outputs.

## Quick start

```bash
# Synthetic demo mode (no input files needed)
python scripts/debris_flow_risk.py --output-dir ./dfr-output

# With custom parameters
python scripts/debris_flow_risk.py \
  --rainfall-scenario 100yr \
  --runout-method geometric \
  --risk-schema three_class \
  --output-dir ./dfr-output

# With custom outlet points
python scripts/debris_flow_risk.py \
  --outlet-points ./outlets.geojson \
  --material-source sparse \
  --output-dir ./dfr-output
```

## License

MIT
