<img src="bento-header.svg?v=2" width="100%"/>

---

### Projects

<table>
<tr>
<td width="50%" valign="top">

#### License Plate Detection & OCR Pipeline
![](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) ![](https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white) ![](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)

End-to-end Russian license plate recognition system

- Custom YOLO training on own dataset (Roboflow)
- SHA-256 deduplication, label validation
- OCR with Russian format post-processing
- Single & double-line plate decoding

</td>
<td width="50%" valign="top">

#### [SocialHub (dister)](https://github.com/OnProGrammer/dister)
![](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white) ![](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

Social platform with microblog, channels & RBAC. Dual API (REST + GraphQL) over shared business logic

- JWT + Refresh Token Rotation, RBAC
- Cursor pagination, BFF pattern
- Redis cache with invalidation
- Optimistic UI, Axios interceptor queue

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [Minecraft Texture AE](https://github.com/OnProGrammer/minecraft-texture-ae)
![](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)

Conv Autoencoder + skip-connections for Minecraft texture generation

- 1111 textures 16×16, upscaled to 160×160
- Dual loss: main (skip) + latent-only (noisy)
- SLERP interpolation between blocks
- val_recon: 0.120 → 0.038 in 7 epochs

</td>
<td width="50%" valign="top">

#### [GitHub RecSys](https://github.com/OnProGrammer/github-recsys)
![](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)

GitHub repository recommendation system

- Matrix Factorization + BPR Loss
- 357K interactions, 201K users
- Hit@20 = 0.43, Recall@20 +70% vs baseline
- Interactive bipartite graph (Plotly)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [Audio Classification](https://github.com/OnProGrammer/audio-classification)
![](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)

CNN on mel-spectrograms: motorcycle vs car. 91% acc

- Multi-worker Selenium YouTube parser
- 3696 clips, stratified split
- Conv2d + BatchNorm + Global Avg Pooling
- L2-normalized embeddings, t-SNE

</td>
<td width="50%" valign="top">

#### [GitHub Issue Classifier](https://github.com/OnProGrammer/github-issue-classifier)
![](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![](https://img.shields.io/badge/BS4-444?style=flat-square&logoColor=white)

Bi-LSTM Kubernetes issue classification (4 classes)

- Scraper: proxy pool with rotation, checkpoint/resume
- BPE tokenization (16K vocab)
- Structured JSON logging (ELK-compatible)
- Graceful shutdown via SIGINT/SIGTERM

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### Python Automation & Traffic Analysis
![](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white) ![](https://img.shields.io/badge/Appium-662D91?style=flat-square&logo=appium&logoColor=white) ![](https://img.shields.io/badge/Frida-FF6600?style=flat-square&logoColor=white) ![](https://img.shields.io/badge/ADB-3DDC84?style=flat-square&logo=android&logoColor=white)

Web & mobile automation toolkit with API analysis

- Browser/mobile automation, proxy, cookies, sessions
- Fiddler/Postman/Wireshark: API analysis & debug
- ADB + Frida: Android traffic instrumentation
- Queue/waiting-room workflow research

</td>
<td width="50%" valign="top">

#### [Berkeley Sockets Server](https://github.com/OnProGrammer/Berkeley)
![](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![](https://img.shields.io/badge/Google_Test-4285F4?style=flat-square&logo=google&logoColor=white) ![](https://img.shields.io/badge/ncurses-333?style=flat-square&logoColor=white)

Multithreaded C++ client-server + dashboard

- Thread pool for parallel connections
- JSON serialization, persistent storage
- Dashboard: CPU, RAM, disk in real time
- Unit tests with thread-safety checks

</td>
</tr>
</table>

<details>
<summary><b>More projects</b></summary>
<br/>

| Project | Description | Stack |
|---|---|---|
| **C++ In-Memory SQL-like DB** | SQL-like DB: std::variant, mutex/shared_mutex, CRUD | C++, STL |
| **Custom Allocator** | Manual memory management, allocation strategies | C++ |
| **Circular Buffer** | Fixed-size ring buffer with producer/consumer semantics | C++ |
| **C++ Networking Prototypes** | Async messenger, broker, file sharing, event loop | C++, Sockets, uWebSockets |
| **Flask Data Collection Service** | Parsing, MySQL, scheduled cleanup, status endpoint | Python, Flask, MySQL |
| **Telegram Bots** | aiogram/telethon bots with async handlers & backend integration | Python, asyncio |
| **Laravel + React Multi-site** | Hub API + ~50 dealer sites, HMAC, webhooks, audit logs | Laravel, React |
| **WordPress / Bitrix** | VPS deploy, PHP customization, MySQL | PHP, WordPress, 1C-Bitrix |
| **Android Museum App** | Kotlin/Java, Gradle, Android lifecycle | Kotlin, Java |

</details>

