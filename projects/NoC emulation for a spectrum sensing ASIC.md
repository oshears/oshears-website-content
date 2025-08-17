---
title: NoC emulation for a spectrum sensing ASIC
pubDate: 2024-10-01
description: An overview of my work to verify and run an NoC design using ESP, Xcelium, and emulation on a various FPGA development boards.
heroImage: /isi.webp
badge: USC ISI
draft: false
tags:
  - FPGA
  - USC-ISI
---


My work on emulating and helping with verification efforts for this ASIC were a part of the [TRACER: Tasklet Reconfigurable Agile speCtrum procEssoR](https://www.isi.edu/projects-tracer/) at USC ISI. This effort was funded by DARPA's PROWESS program.
- [PROWESS: Processor Reconfiguration for Wideband Spectrum Sensing | DARPA](https://www.darpa.mil/research/programs/processor-reconfiguration-for-wideband-spectrum-sensing)
- [SAM.gov](https://sam.gov/opp/d4abfe23e41341ae8b5afecad1114be9/view)


- Emulated [ESP](https://github.com/sld-columbia/esp) NoC on VCU128, VCU118
- integrated and verified custom spectrum sensing accelerator IP using waveforms in Cadence Xcelium/NCSim
- setup [HAPS 100-4F](https://www.synopsys.com/verification/emulation-prototyping/prototyping/haps-100.html#haps-family) with interns

# Relevant Links
- [Home - Tasklet Reconfigurable Agile speCtrum procEssoR (TRACER)](https://www.isi.edu/projects-tracer/)
- [DARPA Eyes Adaptive, Real-Time Processors for Future AI-Enabled Radios](https://www.darpa.mil/news/2022/ai-enabled-radios)
- [Processor Reconfiguration for Wideband Sensor Systems (PROWESS) - SAM.gov](https://sam.gov/opp/d4abfe23e41341ae8b5afecad1114be9/view)
- [ESP - open SoC platform](https://www.esp.cs.columbia.edu/)
- [sld-columbia/esp: Embedded Scalable Platforms: Heterogeneous SoC architecture and IP integration made easy](https://github.com/sld-columbia/esp)
- [HAPS-100: High-Performance Scalable Prototyping System | Synopsys](https://www.synopsys.com/verification/emulation-prototyping/prototyping/haps-100.html#haps-family)