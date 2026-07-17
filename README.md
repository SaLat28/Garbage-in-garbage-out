# Fluid Forecast Reliability — Public Demo

An interactive **"garbage in, garbage out"** demo of a fluid-condition forecasting
model. Pick the machine, then strip its oil-analysis data down (fewer samples,
fewer lab tests) and watch the model's survival forecast, next-value prediction
bands, and a live **trust verdict** degrade as inputs go missing.

- **Single self-contained page** — `index.html` (no server, no dependencies).
- **Synthetic data only.** The one asset ("Mr pumps a lot") uses invented data.
  **No real customer information is present.**
- Every number is a real, precomputed output of the trained model, looked up live.

## Live site

Once GitHub Pages is enabled (Settings → Pages → Deploy from `main` / root):
`https://salat28.github.io/Garbage-in-garbage-out/`

## Local

Just open `index.html` in any browser.
