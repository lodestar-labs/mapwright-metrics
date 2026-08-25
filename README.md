# mapwright-metrics

State for the "Mapwright download milestones" scheduled routine. `state.json` holds the
highest download milestone already announced, so the routine notifies once per new
milestone (10, 100, 1000, ...) instead of on every run. Updated automatically by the routine.
