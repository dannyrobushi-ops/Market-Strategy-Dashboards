# Market Strategy Dashboards

Public GitHub Pages home for the weekly market strategy HTML dashboards.

## Stable Links

- Home: `https://dashboards.apexmacroresearch.com/`
- Command Center: `https://dashboards.apexmacroresearch.com/Chief_Market_Strategist_Command_Center.html`
- Breadth Overview: `https://dashboards.apexmacroresearch.com/Breadth_Dashboard_Overview.html`
- Breadth Individual Charts: `https://dashboards.apexmacroresearch.com/Breadth_Dashboard_Individual_Charts.html`
- ETF Macro Technicals: `https://dashboards.apexmacroresearch.com/etf_macro_technical_chartdeck.html`
- Yield Curve: `https://dashboards.apexmacroresearch.com/yield_curve_institutional_chartdeck.html`
- Volatility Adjusted Momentum Signal (VAMS): `https://dashboards.apexmacroresearch.com/VAMS_Signal_Chartdeck.html`
- CFTC Positioning: `https://dashboards.apexmacroresearch.com/CFTC_Positioning_Institutional_Chartdeck.html`
- Labor Market: `https://dashboards.apexmacroresearch.com/Labor_Market_Overview_Chartdeck.html`
- Fiscal Monitor: `https://dashboards.apexmacroresearch.com/Treasury_Fiscal_Positioning_Chartdeck.html`

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
   - `CFTC_Positioning_Institutional_Chartdeck.html`
   - `Labor_Market_Overview_Chartdeck.html`
   - `Treasury_Fiscal_Positioning_Chartdeck.html`
3. If any dashboard has an assets folder, upload that folder too and keep the folder name/path exactly as the HTML expects.
4. Open the GitHub repository in the browser.
5. Use **Add file -> Upload files**.
6. Drag the nine HTML files, plus any required assets folders, into the repo root.
7. Commit directly to `main`.
8. If readers still see old content, edit `index.html` and update the `?v=YYYYMMDD` values in the nine links to the current weekly date.
9. Give GitHub Pages a minute or two to refresh.

Because the filenames stay the same, Substack links do not need to change each week.

## Suggested Substack Usage

Substack does not support dropping interactive HTML directly into an article. Use a normal link or button-style text in the post, pointing readers to the GitHub Pages URL.

Best default link for posts:

`https://dashboards.apexmacroresearch.com/Chief_Market_Strategist_Command_Center.html`
