# `pr/sip-phone`

One part of the topic repo p1ngb4ck/esphome-phone. The whole topic, with its description, is the branch `main`.

Change of this branch: `sip_phone`: SIP phone (account registration, Opus / G.722 / PCMA / PCMU, contacts, DTMF, messages), sound from a resampler microphone to a speaker

Based on these branches, whose changes it holds and builds on:

- `pr/audio-task-priority` of p1ngb4ck/esphome-audio: decode and resample tasks at priority 2, above the main loop
- `pr/network-priority` of p1ngb4ck/esphome-network: `network` `priority` changeable at runtime and saved, `on_active_interface`, the default route on the first connected interface in that order
