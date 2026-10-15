# PR visuals

Read by the `pr-screenshots` and `pr-demo-video` skills. This file is committed, so keep secrets
out of it: only local or seeded demo accounts belong here.

## App

- URL: http://localhost:5173
- Who starts it: the agent, with `pnpm dev`
- Before capturing: none

## Demo accounts

None needed: the dashboard runs on mock data without a login.

## Capture

- Tool: playwright-cli
- Viewport: 1440x900, device scale factor 2 for screenshots
- PR layout: table
- Section heading: `## Screenshots`
- Accent colour for video callouts: #4f46e5

## Gotchas

- The theme switch is a dropdown: open "Toggle theme", then pick "Dark".
- Every stat card says "from last month"; scope locators to the Total Revenue card.
