# Bnlang Web Socket

A WebSocket implementation for the Bnlang programming language, providing real-time bidirectional communication capabilities for web applications.

---
## 📦 Install

```bash
bpm install bnlang-web-socket
```

Use it in your app:

```bnl
const { createWSServer } = require("bnlang-web-socket");
```

---

## 🚀 Quick start (basic)
```bnl
const { createWSServer } = require("bnlang-web-socket");

const ws = createWSServer({
  path: "/ws",
  heartbeat: 30_000,
  maxPayload: 1048576,
});
```

## License

Bnlang Web Socket is licensed under the [MIT](./LICENSE).