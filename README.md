## Issa Loubani

**I build AI voice agents that answer real phone calls.** Beirut, Lebanon.

I started the AI work at Apliman on my own, while I was in R&D. Customers
liked what came back, demand grew faster than one person could absorb, and the
company built an AI team around it. I wrote the voice agent platform, I still
maintain it, and I onboard the engineers joining the team.

Most of my time goes to real-time audio: Pipecat pipelines in Python, custom
processors and transports, and the turn loop between speech recognition, a
model, and synthesis. The part people underestimate is everything below it —
carrier SIP, Asterisk, AudioSocket, DTMF, ICE and NAT traversal, and the
specific misery of WebRTC inside Docker. A voice agent is a demo until it
survives a real telephony network.

I am a native Arabic speaker, so I do the Arabic evaluation myself. Whether a
synthesised voice reads a phone number correctly, whether it drifts out of
dialect, whether a transcript is right or merely plausible. Benchmark scores
catch none of that.

### Published

[![GLB Viewer downloads](https://img.shields.io/jetbrains/plugin/d/22024?label=glb-viewer%20installs&color=1f6feb)](https://plugins.jetbrains.com/plugin/22024-glb-viewer)
[![pub package](https://img.shields.io/pub/v/arabizi_transliterator?label=arabizi_transliterator&color=1f6feb)](https://pub.dev/packages/arabizi_transliterator)

- **[glb-viewer](https://plugins.jetbrains.com/plugin/22024-glb-viewer)** —
  IntelliJ plugin for inspecting 3D GLB models without leaving the IDE. The
  most-installed GLB viewer on the JetBrains Marketplace.
- **[arabizi_transliterator](https://pub.dev/packages/arabizi_transliterator)** —
  converts Arabizi, the Latin-character Arabic half the region actually types,
  into Arabic script. There is a live demo of it running on my site.
- **[omori-progress-bar](https://plugins.jetbrains.com/plugin/33141)** —
  replaces the IDE progress bar with a themed one. No engineering argument for
  it whatsoever.

### Working with

`Python` `FastAPI` `Pipecat` `WebRTC` `SIP` `Asterisk` `AudioSocket`
`STT / TTS / ASR` `LLM tool calling` `Docker` `Flutter` `Kotlin`

Before voice: three years of Flutter across mobile and web, and a stretch on
WebRTC and TURN infrastructure — Coturn, RTPEngine, ICE, SIPp load testing.

### Elsewhere

[Site](https://issaloubani.github.io) ·
[LinkedIn](https://www.linkedin.com/in/issa-loubani) ·
issa.loubani.5@gmail.com

Open to remote roles and to relocating to the Gulf.
