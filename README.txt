SERMON DEMO — 3 SLIDES

Slides:
1. GOD HAS GIVEN US EVERYTHING — 2 Peter 1:3–4
2. MAKE EVERY EFFORT — 2 Peter 1:5–9
3. STRIVE — final emphasis

FILES
presenter.html  Private speaker notes, navigation, timer, pacing
 audience.html  Audience-only slides
slides.js       Slide text, speaker notes, target durations
sync.js         Browser window synchronization
styles.css      Theme

RUNNING
Host this folder on any ordinary static website under one origin (HTTPS recommended).
Open presenter.html on the iPad and audience.html in a second Safari window on the external display. Both windows must use the same site and browser storage context. Use Stage Manager extended display mode rather than mirroring.

To test on a laptop with Python installed:
  cd sermon_demo
  python3 -m http.server 8000
Then open http://localhost:8000/presenter.html and http://localhost:8000/audience.html in separate browser windows.

Offline: Use a local web server or a previously installed/locally hosted site. Merely opening file:// HTML files is not a reliable synchronization method on iPad Safari. Test with the exact iPad/projector setup before presenting.

Timer starts manually. Slide advances are always manual. No notes are sent to the audience view.
