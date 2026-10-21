### Alonso Sandoval

Co-founder and CTO at [Caudals](https://caudals.com). Telecommunications engineer from the University of Valladolid, software from 42 Madrid, finishing an MSc in telecommunications engineering in 2027.

[alonsosandoval.com](https://alonsosandoval.com) · [blog](https://alonsosandoval.com/blog) · [linkedin](https://www.linkedin.com/in/alonso-sandoval-martinez/)

---

#### Now: Caudals

Companies deploy assistants and agents on top of their own documentation and ship them after a demo that looked fine. Caudals finds where they fail before customers do: golden test sets written from the company's real documents and validated by people from the sector, run against the system, with evidence of what broke and why. Then we build the expert data that was missing. Winner of Campus Emprendedor and the Santander X round at the University of Valladolid, member of NVIDIA Inception. The code is in [Caudals/caudals](https://github.com/Caudals/caudals).

Along the way we built our own prospecting agent on a DGX Spark with Hermes and a quantised DeepSeek, and learned the same lesson we sell: getting an agent to run takes an afternoon; knowing whether to trust it takes evaluation. [That story](https://alonsosandoval.com/blog/prospecting-agent).

#### Payments: SEPA Request-to-Pay

Bachelor's thesis, 10/10 with highest honors. SEPA Request-to-Pay is the European Payments Council's scheme for asking for a payment before it happens: the payee sends a structured request, the payer's bank presents it in the banking app, the payer accepts under strong customer authentication, and an instant credit transfer settles it. I specified the scheme from the rulebook step by step, measured it against SEPA Direct Debit on its structural costs, and implemented a service provider across the four corners, with rejects, expiry and cancellation. The flow is animated, step by rulebook step, at [alonsosandoval.com/rtp](https://alonsosandoval.com/rtp).

→ [sepa-request-to-pay](https://github.com/asandova-ui/sepa-request-to-pay)

#### Radio and systems: a connected vehicle on a private LTE network

A 4G core and an eNodeB on a bladeRF, built with srsRAN; a small car attached as user equipment; a traffic-sign detector trained on a dataset we built, served from a Jetson; every driving decision taken in the core, with lane assistance, an IMU-based speed loop and LiDAR safety layered on top. Then the same service planned for the 104 km of the A-601: traffic forecast from the Ministry's counting stations, radio planning in Xirio with 25 sites, cost and licensing. With Mario Medrano and Luis F. Sánchez.

→ [connected-vehicle-private-lte](https://github.com/asandova-ui/connected-vehicle-private-lte) · [project site, with the demo](https://asandova-ui.github.io/connected-vehicle-private-lte/)

#### Software: the 42 Madrid common core

Two years of C, Unix, networking and C++ alongside the degree, with no teachers and no classes: a project, a subject, a deadline, and other students grading you. A libc, `printf`, a shell with pipes and heredocs, dining philosophers, a Wolfenstein-style raycaster, an IRC server in C++98 on `poll()`, a containerised web stack, and a full-stack final project in a team of four. Every project validated; the whole graph, project by project, at [alonsosandoval.com/42](https://alonsosandoval.com/42).

→ [42-madrid-common-core](https://github.com/asandova-ui/42-madrid-common-core)

#### Hardware

- [handheld-retro-console](https://github.com/asandova-ui/handheld-retro-console): an LPC2106 on a custom two-layer PCB, an 800×480 TFT, two D-pads, stereo audio synthesised in software on the PWM, haptics, a Li-Po and a resin case. Bare-metal C drivers and a Pac-Man written for the platform. With Mario and Luis.
- [fpga-lora-telemetry-node](https://github.com/asandova-ui/fpga-lora-telemetry-node): four stacked boards, a RISC-V soft core on an iCE40, five environmental sensors and a GPS, an SX1262 radio with a meander antenna etched on the board, simulated in HFSS and trimmed on a VNA to 868 MHz. Team of five.
- [larva-riscv-multiplier](https://github.com/asandova-ui/larva-riscv-multiplier): the laRVa RISC-V core multiplied one bit per clock; this unit takes four, with the same ports, so a 32×32 product costs eight cycles instead of thirty-two. Verified in a 44-case bench and inside the running CPU. With Andrés.

#### Signal processing

- [matlab-audio-workbench](https://github.com/asandova-ui/matlab-audio-workbench): an audio workbench in App Designer, six signals at a time: record, synthesise, filter, resample, modulate, quantise, add effects, transcribe. With Mario.

---

Before Caudals I spent two years at a payments fintech, where I led the AI side: models and data pipelines over transaction data, and the first LLM-based tools for the back office. The thesis on Request-to-Pay came out of that period.

I write occasionally about payments, AI evaluation and what we are building: [alonsosandoval.com/blog](https://alonsosandoval.com/blog).
