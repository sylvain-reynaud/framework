# Evidence

Capture one artifact per screen, per state.

## States to cover

| State | What to capture |
| --- | --- |
| First use | the screen as seen before any data or history exists |
| Empty | the screen with zero data and no error |
| Loading | the screen mid-fetch or mid-transition |
| Error | the screen after a failed action or fetch |
| Success | the screen after a completed action |
| Return visit | the screen as seen by a returning persona with history |

## Viewport

When a url is given, capture both a desktop and a mobile viewport for every screen and state.

## Screenshot naming

`<screen-slug>_<state>_<viewport>.png`, for example `dashboard_empty_mobile.png`.
