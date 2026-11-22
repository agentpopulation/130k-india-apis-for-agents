# Changelog

## 2026-11-15 (snapshot-2026-11-15)

- New snapshot: 131,489 endpoints from 2,180 services, tested 10–15 Nov 2026 (IST), snapshot 15 Nov 2026; 129,980 more endpoints than the 14 Nov 2026 release (1,509 endpoints from 138 services).
- Rebuilt under the same snapshot with the latest leave-out rules (other addresses of a left-out ArcGIS layer, teaching organisations, more class-layer, name and record rules): 131,136 endpoints from 2,126 services, 353 fewer endpoints than first published under this snapshot (131,489 from 2,180 services), tested 10–15 Nov 2026 (IST).
- The repository holds a 1,000-row sample and the services list; the full list is the release download India_API_Endpoints_AgentPopulation_Snapshot_2026-11-15.csv.gz.
- GitHub name: 130k-india-apis-for-agents (was india-api-endpoints).
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

## 2026-11-14 (snapshot-2026-11-14)

- First release: 1,509 endpoints from 138 services, tested 10–14 Nov 2026 (IST), snapshot 14 Nov 2026.
- The repository holds a 503-row sample and the services list; the full list is the release download India_API_Endpoints_AgentPopulation_Snapshot_2026-11-14.csv.gz.
