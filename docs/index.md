---
layout: default
---

<style>
  .tiles {
    display: grid;
    grid-template-columns: 1fr;
    gap: 1.5rem;
    margin: 2rem 0;
  }
  @media (min-width: 600px) {
    .tiles { grid-template-columns: 1fr 1fr; }
  }
  .tile {
    border: 1px solid #e1e4e8;
    border-radius: 6px;
    padding: 1.25rem 1.5rem;
    transition: box-shadow 0.15s ease, transform 0.15s ease;
  }
  .tile:hover {
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.08);
    transform: translateY(-1px);
  }
  .tile h2 {
    margin-top: 0;
    margin-bottom: 0.5rem;
    font-size: 1.25rem;
  }
  .tile h2 a { text-decoration: none; }
  .tile p {
    color: #586069;
    margin-bottom: 1rem;
    font-size: 0.95rem;
  }
  .tile ul {
    list-style: none;
    margin: 0;
    padding: 0;
  }
  .tile li { margin: 0.25rem 0; }
</style>

<div class="tiles">
  <div class="tile">
    <h2><a href="/video-call-calendar-auto-call/">Video Call Calendar Auto Call</a></h2>
    <p>Chrome extension that auto-opens your Google Meet calls with a ringtone right when meetings start, so you can stay in flow until it's time.</p>
    <ul>
      <li><a href="/video-call-calendar-auto-call/">Project page</a></li>
      <li><a href="/video-call-calendar-auto-call/privacy/">Privacy policy</a></li>
      <li><a href="/video-call-calendar-auto-call/terms/">Terms of service</a></li>
      <li><a href="/video-call-calendar-auto-call/limited-use/">Limited use policy</a></li>
    </ul>
  </div>

  <div class="tile">
    <h2><a href="/open-calendar-slots/">Open Calendar Slots</a></h2>
    <p>Chrome extension that reads your Google Calendar, finds the gaps between meetings, and gives you a clean list of open times to paste into any message.</p>
    <ul>
      <li><a href="/open-calendar-slots/">Project page</a></li>
      <li><a href="/open-calendar-slots/privacy/">Privacy policy</a></li>
      <li><a href="/open-calendar-slots/terms/">Terms of service</a></li>
      <li><a href="/open-calendar-slots/limited-use/">Limited use policy</a></li>
    </ul>
  </div>
</div>
