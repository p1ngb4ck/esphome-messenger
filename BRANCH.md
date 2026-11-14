# `pr/messenger`

One part of the topic repo p1ngb4ck/esphome-messenger. The whole topic, with its description, is the branch `main`.

Change of this branch: `messenger`: the messenger app (Telegram, WhatsApp, Facebook Messenger; bot, Home Assistant or account transport; calls through sip_phone and the camera's H.264 stream)

Based on these branches, whose changes it holds and builds on:

- `pr/mtproto`: `mtproto`: Telegram MTProto client (crypto, TL schema, QR login)
- `pr/camera-encoder-h264` of p1ngb4ck/esphome-esp-video: camera, camera_encoder: H.264 streams on the P4's hardware encoder
- `pr/sip-phone` of p1ngb4ck/esphome-phone: `sip_phone`: SIP phone (account registration, Opus / G.722 / PCMA / PCMU, contacts, DTMF, messages), sound from a resampler microphone to a speaker
- `pr/storage` of p1ngb4ck/esphome-storage-interface: the `storage` component: registry, path / filesystem / network / raw storages, the asynchronous worker (jobs, streams), `storage.*` actions, PSRAM transfer buffer, change feed, ISO 9660 mount
