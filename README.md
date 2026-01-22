# GhostSignal

**GhostSignal** is a protocol for embedding and extracting structured data directly from media streams such as video and audio.

It enables media itself to carry data — independently of platforms, trackers, or external APIs.

A project by **Patternity**.

---

## Why GhostSignal

Media dominates the web, but it is effectively *data-blind*.

Today, attribution, analytics, coupons, and Web3 interactions rely on:
- redirects and tracking links
- platform-specific APIs
- external metadata detached from the content itself

GhostSignal introduces a native **data layer inside the media stream**.

---

## What It Enables

- Proof-of-watch / proof-of-play
- Embedded campaign identifiers
- Coupons and claims carried by the content
- Privacy-first attribution
- Web3 minting and claims without links or QR codes

The data travels with the media — wherever it goes.

---

## How It Works (High Level)

1. Structured data is encoded into the media stream using a deterministic transport.
2. The media is distributed normally (files, streams, platforms).
3. A decoder (browser extension, SDK, or app) extracts the embedded data locally.
4. Applications react to the extracted signal.

No platform integration required.

---

## Protocol Status

- **Status:** Draft (v0)
- **Current transport:** Visible Byte Band (VBB) for demonstration purposes

See the protocol specification:

👉 [`spec/v0.md`](./spec/v0.md)

---

## Demo

A reference browser-based demo is under development.

The demo demonstrates:
- encoding data into a video stream
- extracting data from the recorded video
- real-time visualization of the decoding process

Demo repository (coming soon):
👉 `ghost-signal-demo`

---

## Direction (Non-binding)

Possible next directions (not commitments):

- Additional transports (less visible / more robust)
- Error correction and resilience to transcoding
- Optional authenticity (hashing, signatures)
- Tooling: encoder/decoder SDKs and reference implementations
- Browser extensions and application integrations

---

## Part of Patternity

GhostSignal is developed under **Patternity** — a research and engineering organization focused on hidden patterns, signals, and behavioral structures in interactive systems.

---

## License

Apache License 2.0
