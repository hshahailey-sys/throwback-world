# Throwback World

A 2016-inspired blocky social game starter with Three.js, town/obby scenes, WebSocket player presence and chat.

## Deploy
This repository includes a Render Blueprint (`render.yaml`). Open Render's Blueprint deployment flow and connect this repository. Render free instances may sleep when idle and do not provide durable local disk by default.

## Important prototype limitations
This commit is a prototype, not a public-ready launch. The current account endpoint only reserves usernames; it does not implement password login or secure sessions. It writes users to local JSON, which is not durable on ephemeral hosting. Do not use real passwords or sensitive personal information. A persistent database and proper authentication must be added before public launch. Murder Mystery is a lobby placeholder, not complete rounds.

## Android
The Android wrapper and APK build workflow are planned separately; this repository currently hosts the web server source only.
