# SDK — INSTRUMENT.VNA

Every VNA model this library drives, and how to drive it. Each model answers the same five verbs over HTTP (its own port), WebSocket, a Unix socket and the bus; one page per model below lists its routes and every command.

← [Manual and Artifacts](INDEX.md)

| Verb | What it does |
|---|---|
| `get` | reads one value |
| `set` | writes one value |
| `nab` | reads more than one thing (observation, telemetry) |
| `rig` | configures several arguments at once |
| `do` | executes an action; takes no value |

| Model | Maker | get | set | nab | rig | do | Port |
|---|---|---:|---:|---:|---:|---:|---:|
| [8720ES](SDK/8720ES.md) | HP / Agilent / Keysight | 5 | 9 | 6 | 1 | 7 | 16200 |
| [8753E](SDK/8753E.md) | HP / Agilent / Keysight | 5 | 9 | 6 | 1 | 7 | 16201 |
| [E5061B](SDK/E5061B.md) | HP / Agilent / Keysight | 5 | 9 | 6 | 1 | 7 | 16202 |
| [E5071C](SDK/E5071C.md) | HP / Agilent / Keysight | 5 | 9 | 6 | 1 | 7 | 16203 |
| [E8361C](SDK/E8361C.md) | HP / Agilent / Keysight | 5 | 9 | 6 | 1 | 7 | 16204 |
| [N5221B](SDK/N5221B.md) | HP / Agilent / Keysight | 5 | 9 | 6 | 1 | 7 | 16205 |
| [N5222B](SDK/N5222B.md) | HP / Agilent / Keysight | 5 | 9 | 6 | 1 | 7 | 16206 |
| [N5245B](SDK/N5245B.md) | HP / Agilent / Keysight | 5 | 9 | 6 | 1 | 7 | 16207 |
