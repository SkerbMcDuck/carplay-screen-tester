# CarPlay screen tester

A one-page test bench for checking how web pages behave on a car screen through CarBridge.

Open the live page in Safari on the phone, then use Share → Add to Home Screen to run it full screen.

Tabs:
- **Screen**: usable size, safe areas, and edge markers to spot cropping
- **Touch**: touch pad with response time and the most fingers seen at once
- **Buttons**: hit rates for five button sizes
- **Text**: readable sizes at a glance
- **Sound & sensors**: car speaker test (tone, left, right, voice, media), motion sensor, keep screen on

**Copy report** on the Screen tab collects every result to paste back.

## Car Home (`/dash/`)

A car home screen: a live Google map with search on the left, Spotify controls and minutes to home and work on the right. Tapping Home, Work or a search result hands off to the Google Maps app for turn-by-turn directions.
Needs a Google Maps key (restricted to this site) for the map, search and live-traffic times; without one it falls back to normal-traffic estimates.
Settings stay on the phone only; nothing personal is stored in this repo.
