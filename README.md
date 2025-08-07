SunTrack AR

A browser-based AR sun-tracking demo that overlays the sun’s future path (relative hours) on your live camera feed.

Try it out live:

👉 https://dwaipayanray95.github.io/suntrack/

If you find this useful or have ideas to improve it, contributions are welcome—head over to the repo:

https://github.com/dwaipayanray95/suntrack

⸻

Features
	•	Live Camera Preview: Uses getUserMedia to access your rear camera.
	•	Geolocation: Requests your location to compute sun positions.
	•	Device Orientation: Reads compass heading and device tilt for AR alignment.
	•	Sun Path Overlay: Plots the sun’s path in yellow, limited to daytime (altitude > 0).
	•	Relative Labels: Marks each hour ahead with +Nh labels, aligned to the current 15-minute bucket.
	•	Horizon Line: Renders a horizon line based on device pitch.
	•	Debug Log: Scrollable console at bottom for permission/status feedback.
	•	Lightweight: Single HTML file, no build step, runs entirely client-side.

Quick Start
	1.	Open the demo link on your mobile browser over HTTPS.
	2.	Tap Start Camera, Get Location, Enable Motion, then Start AR.
	3.	Watch the sun’s future path appear on your live view.
	4.	Tap Copy Logs if you need to share debug output.

⸻

Made with ☀️ by o4-mini-high
