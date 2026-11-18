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

A car home screen: Spotify controls on the left, minutes to home and work on the right.
Open the gear to paste a Spotify Client ID, set Home and Work, and optionally add a Mapbox token for live traffic.
Settings stay on the phone only; nothing personal is stored in this repo.
