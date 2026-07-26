<p align="center">
  <img src="https://raw.githubusercontent.com/twigo/twigo/main/apps/twigo/src-tauri/icons/128x128@2x.png" width="120" alt="Twigo" />
</p>
<h1 align="center">Twigo</h1>
<p align="center"><b>A fast, keyboard-first desktop IDE for NATS.</b></p>

Open source, built with Tauri and Rust. It reads the contexts your `nats` CLI
already has, so connection details never live in two places.

- **Messaging** — subject explorer built from live traffic, subscriptions,
  publish and request/reply, a JSON/text/hex viewer that diffs any two messages
- **JetStream** — streams and consumers, plus a message browser that never
  creates a consumer and never moves an ack floor
- **KV and Object Store** — both read and write, with KV revision history
- **Payload codecs** — Protobuf, MessagePack and CBOR, decoding _and_ encoding
- **Responders** — mock a service by answering a subject from a template
- **Monitoring** — varz, connz and jsz, with throughput and consumer lag
  charted over time rather than sampled once

### Get it

Download from the [**Releases**](https://github.com/twigo/twigo/releases/latest)
page — macOS and Linux today, Windows not packaged yet. The
[main repository](https://github.com/twigo/twigo) covers building from source
and contributing.
