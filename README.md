# Members Gate

A cabinet screen. Each kind is checked alone. A spare does not cover a missing kind.

A job can total out and still be short. Play while you wait.

## Current Status (2026-11-08) — Residual-Honest

| Surface | Status |
|---------|--------|
| Live screen | `index.html` (closed-case runner) |
| Results view | `results.html` |
| Scope | Demonstration of the per-kind headroom check. Not a grant. No price printed. |
| Related IP | Members Gate PPA 64/169,264 (filed/paid 2026-10-04). Separate from MAGPIE 19/658,750 and Headroom 64/150,688. |
| Honesty | Browser toy / teaching cabinet. Totals are not the check. |

## How it works

Paste rows of the form:

```
label,claimed,interior
```

Each row is evaluated independently. If any row has headroom < 0 the whole case is **REFUSE**. A surplus on one kind cannot pay for a shortage on another.

## Local

Open `index.html` in a browser or serve the folder:

```bash
python3 -m http.server 8080
```

## Related

- Headroom admission control demonstration: https://github.com/snowphamtom/refuse
- Spatial / WebXR visualization of the same gate: https://github.com/snowphamtom/vr-gatekeeper

By Taylor Heller / Monsters Ink LLC
