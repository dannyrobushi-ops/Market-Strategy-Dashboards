# Market Strategy Dashboards

Public GitHub Pages home for the weekly market strategy HTML dashboards.

## Stable Links

- Home: `https://dannyrobushi-ops.github.io/Market-Strategy-Dashboards/`
- Command Center: `https://dannyrobushi-ops.github.io/Market-Strategy-Dashboards/Chief_Market_Strategist_Command_Center.html`
- Breadth Overview: `https://dannyrobushi-ops.github.io/Market-Strategy-Dashboards/Breadth_Dashboard_Overview.html`
- Breadth Individual Charts: `https://dannyrobushi-ops.github.io/Market-Strategy-Dashboards/Breadth_Dashboard_Individual_Charts.html`
- ETF Macro Technicals: `https://dannyrobushi-ops.github.io/Market-Strategy-Dashboards/etf_macro_technical_chartdeck.html`
- Yield Curve: `https://dannyrobushi-ops.github.io/Market-Strategy-Dashboards/yield_curve_institutional_chartdeck.html`
- Volatility Adjusted Momentum Signal (VAMS): `https://dannyrobushi-ops.github.io/Market-Strategy-Dashboards/VAMS_Signal_Chartdeck.html`

The homepage buttons include a weekly `?v=YYYYMMDD` cache-buster so readers click through to the newest uploaded files instead of a stale browser cache.

## Weekly Update Workflow

1. Run the local dashboard scripts.
2. Confirm the output files have these exact names:
   - `Chief_Market_Strategist_Command_Center.html`
   - `Breadth_Dashboard_Overview.html`
   - `Breadth_Dashboard_Individual_Charts.html`
   - `etf_macro_technical_chartdeck.html`
   - `yield_curve_institutional_chartdeck.html`
   - `VAMS_Signal_Chartdeck.html`
3. If any dashboard has an assets folder, upload that folder too and keep the folder name/path exactly as the HTML expects.
4. Open the GitHub repository in the browser.
5. Use **Add file -> Upload files**.
6. Drag the six HTML files, plus any required assets folders, into the repo root.
7. Commit directly to `main`.
8. If readers still see old content, edit `index.html` and update the `?v=YYYYMMDD` values in the six links to the current weekly date.
9. Give GitHub Pages a minute or two to refresh.

Because the filenames stay the same, Substack links do not need to change each week.

## Suggested Substack Usage

Substack does not support dropping interactive HTML directly into an article. Use a normal link or button-style text in the post, pointing readers to the GitHub Pages URL.

Best default link for posts:

`https://dannyrobushi-ops.github.io/Market-Strategy-Dashboards/Chief_Market_Strategist_Command_Center.html`
