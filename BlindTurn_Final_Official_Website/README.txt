BLINDTURN — SMART BLIND-TURN VEHICLE SAFETY SYSTEM

Files
- index.html: complete static website and dashboard.

Deploy
1. Extract this ZIP.
2. Upload the extracted folder (with index.html at its root) to a static host such as Netlify Drop.
3. Open the public URL and test each tab.

Live serial data
- The dashboard uses browser Web Serial in supported desktop browsers such as Chrome or Edge.
- Connect the Road ESP32 by USB to the same computer, grant port permission, and use the expected 115200 baud JSON telemetry.
- Public hosting does not make a locally connected USB device remotely accessible to other viewers. Remote live telemetry requires an additional backend/network transport.

Safety limitations
- The full-screen color overlays are visual alerts only. Physical braking requires compatible vehicle-side ESP32 firmware, motor driver integration, and verified testing.
- Prototype thresholds are configured demonstration rules, not validated real-road safety limits.
- Record measured test results before making performance claims.

Prepared by Chamarthy Ramdev
