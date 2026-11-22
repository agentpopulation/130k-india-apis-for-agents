## India API endpoints, snapshot 15 Nov 2026

- 131,136 endpoints passed a keyless data call, tested 10–15 Nov 2026 (IST)
- 2,126 services · country IN · 32,471 keyless JSON rows

### Download

- `India_API_Endpoints_AgentPopulation_Snapshot_2026-11-15.csv.gz`: the full list, 131,136 rows, 2.2 MB gzipped (31.6 MB as CSV), SHA-256 `d14c7fca07c11c49454999956d3ca22798619a5cf00f86e1b8fd7c7791aa9d23`
- `SHA256SUMS.txt`: the checksum of that file

Check the download in the folder that holds both files:

```bash
sha256sum -c SHA256SUMS.txt          # Linux
shasum -a 256 -c SHA256SUMS.txt      # macOS
certutil -hashfile India_API_Endpoints_AgentPopulation_Snapshot_2026-11-15.csv.gz SHA256   # Windows: compare with SHA256SUMS.txt
```

Then `gunzip India_API_Endpoints_AgentPopulation_Snapshot_2026-11-15.csv.gz` and pass the CSV path to the examples or to `node tools/test-endpoints.mjs`. The repository itself holds a 1,000-row sample and the services list.

### What's in it for you

- 🤖 Agent tools: 261 · Wrap a METAR or TAF URL as a get_airport_weather tool: pass the ICAO code (VIDP, VABB), return the latest report.
- 📱 App features: 7,936 · Show river readings, map layers and transport layers in an app.
- 🧠 Grounding and data pipelines: 6,252 · Load government open-data records on a schedule into your own store.
- 🧪 Evals and testing: 131,136 · Run your tool calls against a fixed set of URLs across formats and record which answer; last_tested is the baseline for your own re-tests.

### Changes

- New snapshot: 131,489 endpoints from 2,180 services, tested 10–15 Nov 2026 (IST), snapshot 15 Nov 2026; 129,980 more endpoints than the 14 Nov 2026 release (1,509 endpoints from 138 services).
- Rebuilt under the same snapshot with the latest leave-out rules (other addresses of a left-out ArcGIS layer, teaching organisations, more class-layer, name and record rules): 131,136 endpoints from 2,126 services, 353 fewer endpoints than first published under this snapshot (131,489 from 2,180 services), tested 10–15 Nov 2026 (IST).
- Left out: 411 rows with a private or local address.
- Left out: 61 ArcGIS Survey123 layers (they can hold people's form answers).
- Left out: 8 ArcGIS layers that keep a form's default service name (they can hold people's form answers).
- Left out: 117 rows that passed a data call only from a network location in India.
- Left out: 62 ArcGIS class or coursework layers (lab, assignment, exam, quiz, lesson, exercise, tutorial and final-project layers, copies of class layers, layers named for a person or a person's home, and layers whose name ends in a person's name or holds a student number).
- Left out: 10 ArcGIS layers that hold reports, comments, submissions or form responses sent in by the public.
- Left out: 1 ArcGIS layer that is a record about named people (employee, patient, client or donor lists, home addresses, voter lists, sex offender and missing person layers).
- Left out: 360 rows of server information from Mastodon, PeerTube, Lemmy, Nostr and other social network servers (instance documents name the server's contact person).
- Left out: 5 rows of ArcGIS Online organisations that are class accounts (25 layers or more, at least 50% of them class or coursework layers): their other layers are students' work too.
- Left out: 82 rows of ArcGIS Online organisations that are class accounts (3 class sets or more in at least 20% of their rows, 10 class sets or more with no organisation name, or layers signed by students read by hand): their other layers are students' work too.
- Left out: 6 rows of class sets: one map layer saved under 5 or more students' initials or names in one ArcGIS Online organisation, or in 4 or more students' own organisations.
- Left out: 251 rows of the ArcGIS Online organisations of universities, colleges and schools (many of their layers are students' work).
- Overlap: 1,857 of these URLs are also in 170k-weather-apis-for-agents.
- Overlap: 404 of these URLs are also in 240k-transit-apis-for-agents.
- Overlap: 1,795 of these URLs are also in 260k-water-apis-for-agents.
- Overlap: 4,549 of these URLs are also in 120k-finance-economy-apis-for-agents.
- Overlap: 4,947 of these URLs are also in 1.2m-government-open-data-apis.
- Overlap: 1,967 of these URLs are also in 270k-statistics-apis-for-agents.
- Overlap: 1,115 of these URLs are also in 84k-oceans-apis-for-agents.
- Overlap: 15 of these URLs are also in 22k-maritime-apis-for-agents.
- Overlap: 568 of these URLs are also in 160k-environment-apis-for-agents.
- Overlap: 11 of these URLs are also in 19k-air-quality-apis-for-agents.
- Overlap: 6,167 of these URLs are also in 350k-maps-gis-apis-for-agents.
- Overlap: 32,406 of these URLs are also in 2.2m-agent-ready-apis.
- Overlap: 2,057 of these URLs are also in 84k-health-apis-for-agents.
- Overlap: 109,513 of these URLs are also in 380k-science-apis-for-agents.
- Overlap: 53 of these URLs are also in 40k-hazards-apis-for-agents.
- Overlap: 2 of these URLs are also in 4.9k-wildfire-apis-for-agents.
- Overlap: 54 of these URLs are also in 67k-energy-apis-for-agents.
- Overlap: 307 of these URLs are also in 23k-aviation-apis-for-agents.
- Overlap: 59 of these URLs are also in 22k-traffic-apis-for-agents.
- Overlap: 28 of these URLs are also in 10k-parking-apis-for-agents.
- Overlap: 11 of these URLs are also in 7.8k-earthquake-apis-for-agents.
- Overlap: 8 of these URLs are also in 17k-bike-share-apis-for-agents.

On the date in last_tested (IST), one GET to the URL, sent with no key, returned HTTP 2xx and a non-empty data body. HTML pages and empty results did not pass. The format column records what came back. This is a test result for that date, not a promise that the URL answers today. Licences, terms, rate limits, accuracy and freshness were not reviewed. Endpoints are URLs, not separate APIs; many share one service. This pack was tested 10–15 Nov 2026; snapshot 15 Nov 2026.

For the latest tested endpoints, search agentpopulation.com/apis. This pack is a snapshot from 15 Nov 2026.

Credit: India API endpoints by AgentPopulation (https://agentpopulation.com), CC BY 4.0, snapshot 15 Nov 2026.

Compiled by [AgentPopulation](https://agentpopulation.com) with [AP Desk](https://github.com/agentpopulation/apdesk) · corrections: [@agentpopulation](https://x.com/agentpopulation) on X
