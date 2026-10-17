- Add a keyless SA Road Events layer (Movement group, off by default) showing
  Traffic SA roadworks, incidents, road closures and detours across South
  Australia. Incidents and closures show by default; both roadworks kinds
  (24 h and long-term, about 1,300 today) sit behind row chips that show how
  many are hidden. Markers and ground-clamped lines are coloured by kind, and
  clicking one shows its road, direction, lanes closed, speed limit and
  Adelaide-time start and end. The row shows the feed's last-updated time.
  `/api/sa-road-events` pages the ArcGIS MapServer past its 1,000-record cap,
  replaces the snapshot only when every page arrives, serves the last good
  snapshot as stale for up to six hours, and uses the identical mirror service
  only if the primary fails. Data: Traffic SA, Department for Infrastructure and
  Transport, Government of South Australia (CC BY 4.0) (bennypixel, #1090).
