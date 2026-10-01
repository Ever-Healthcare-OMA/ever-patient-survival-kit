# Ever Patient Medical Knowledge Survival Kit

A portable, English-language medical reference library with optional local chat.

[Download the kit](https://github.com/Ever-Healthcare-OMA/ever-patient-survival-kit/releases/download/v0.1.0-preview/Ever-Patient-Survival-Kit.zip) · [SHA-256 checksums](https://github.com/Ever-Healthcare-OMA/ever-patient-survival-kit/releases/download/v0.1.0-preview/SHA256SUMS)

The kit contains 509 reference entries from 44 knowledge files, including first aid, emergencies, crisis and conflict, family care, and chronic conditions.

1. Download and extract the ZIP.
2. Open `index.html` to browse and search the library offline.
3. For local chat, install Python 3 and [Ollama](https://ollama.com/) while online, then download a supported model with `ollama pull qwen2.5:3b` or `ollama pull llama3.2:3b`.
4. Start Ollama and run `Start.command` on macOS, `Start.bat` on Windows, or `start.sh` on Linux. The included `README.txt` explains setup and troubleshooting.

Python, Ollama, and model weights are separate downloads. Once setup is complete, reading and chat use your laptop. Chat calls the local Ollama runtime and has no cloud fallback. Conversations are held in memory by the kit, without patient accounts or kit telemetry.

This is an **educational preview**. Independent clinical approval of the existing reference corpus has not been verified. Generated answers can be wrong and do not replace a qualified clinician. Seek emergency assistance for urgent symptoms. Source attribution and reference dates are preserved; they do not establish clinical certification.

The source application remains in the development repositories. This repository distributes the portable kit, its checksums, and its release manifest. Windows and Linux launcher behavior is covered by source checks; native installation on those platforms has not been independently tested.

Copyright Ever Healthcare. All rights reserved. Third-party source attribution remains with the reference entries; Python, Ollama, and model licenses remain with their respective publishers.
