# Frontier-Grade Open Weights

**They Matched the Frontier. But No One Can Hold Them.**

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Language](https://img.shields.io/badge/Language-Japanese%20%7C%20English-blue)](docs/)
[![Last Updated](https://img.shields.io/badge/Last%20Updated-2026--08--20-brightgreen)](https://github.com/Leading-AI-IO/frontier-grade-open-weights/releases)

<p align="left">
  <img src="./assets/ogp_design.png" width="80%">
</p>

*Read this in other languages: [日本語](README.md)*

---

> **Definition**
>
> **This book** is a structural analysis by Satoshi Yamauchi (山内怜史), AI
> Strategist, examining Moonshot AI's July 2026 release of Kimi K3 (2.8T
> parameters, the largest open-weight model to date), which independent
> evaluators listed as "weights not publicly available" and "License:
> Proprietary" on announcement day. The book coins the term "Privileged
> Open" for a state where weights are nominally open but physical, legal,
> evidentiary, and regulatory barriers prevent real access. As stated in
> the closing chapter: "What moved was not the ownership of the model. It
> was the location of scarcity."
>
> *Author & full catalog: [github.com/Leading-AI-IO](https://github.com/Leading-AI-IO)*

---

## 📖 Overview

On July 17, 2026, China's Moonshot AI announced Kimi K3, a 2.8-trillion-parameter model. Independent evaluations placed it close to the world's frontier models, and it ranked first in frontend coding. The market interpreted the announcement as the moment open weights reached the frontier. Yet at the time of the announcement, the weights had not been released.

**This book was written during those ten days before release.** The weights were published as promised on July 27, 2026, in MXFP4 format (1.56 TB), and the license (Kimi K3 License) was disclosed at the same time. All three of the book's predictions held: the weight size, the persistence of the 64-accelerator requirement, and the presence of threshold clauses. The retrospective verification is recorded in the addenda to Chapters 3 and 4.

This book is not about a simple contest between open and closed models. Even when the weights are published, only a limited set of actors can store 2.8 trillion parameters, run them across 64 or more accelerators, independently evaluate the model, and deploy it commercially. **It is published, yet inaccessible.** This book names that condition **“Privileged Open.”**

Drawing on primary sources and independent data, the book examines the capability gap between open-weight and closed models; the boundary between self-reported benchmarks and independent measurement; the physical, institutional, evidentiary, and regulatory barriers surrounding frontier-scale models; the revenue structure of AI labs; the unverified allegations surrounding distillation; AI policy in the United States, China, and Europe; and the developer ecosystem shifting toward Chinese open models.

Its central thesis is simple: **what moved was not model ownership, but the location of scarcity.** As intelligence becomes commoditized, proprietary business context, first-hand information, operational capability, and the judgment required to verify claims become more valuable. This open-source book asks what remains scarce—and who wins—in a world where the frontier has opened without becoming truly “open.”

**Addendum (August 17, 2026): The premise of scale now requires qualification.** 
On August 14, 2026, Z.ai announced GLM-5.3. Official developer documentation positions the model's programming and agentic capabilities as "on par with Claude Fable 5." Its base model is identical to GLM-5.2, at roughly 744B parameters — **about one quarter of Kimi K3's 2.8 trillion.** The book's implicit premise, that frontier-grade performance requires frontier-grade mass, now requires qualification. Yet the weights remain unreleased and no license text exists, so whether the physical wall has lowered is something no one can yet measure. And where Kimi K3 released first and bound afterward by license text, GLM-5.3 partitions the release itself by time, before issuing any text — **the second form of Privileged Open.** The verification is recorded in Addendum 2 to Chapters 3 and 4.

---

## 📄 Document

| File | Language | Content |
| --- | --- | --- |
| [frontier-grade-open-weights_JP.md](./docs/jp/frontier-grade-open-weights_JP.md) | 🇯🇵 Japanese | Full text (Japanese edition) |
| [frontier-grade-open-weights_EN.md](./docs/en/frontier-grade-open-weights_EN.md) | 🇺🇸 English | Full text (English edition) |

---

## 🔄 Update History

This is a **continuously observed** open-source book. Because its subject is still in motion, each new fact is added as an addendum, and **each version records whether the earlier text held or failed.**

| Version | Date | Contents |
| --- | --- | --- |
| [**v1.3**](https://github.com/Leading-AI-IO/frontier-grade-open-weights/releases/tag/v1.3) | 2026-08-20 | Removed solicitation section |
| [**v1.2**](https://github.com/Leading-AI-IO/frontier-grade-open-weights/releases/tag/v1.2) | 2026-08-17 | Added GLM-5.3 (Chapters 3 and 4) |
| [**v1.1**](https://github.com/Leading-AI-IO/frontier-grade-open-weights/releases/tag/v1.1) | 2026-07-28 | Added the weight release and license confirmation (Chapters 3 and 4) |
| [**v1.0**](https://github.com/Leading-AI-IO/frontier-grade-open-weights/releases/tag/v1.0) | 2026-07-23 | Initial release |

See [Releases](https://github.com/Leading-AI-IO/frontier-grade-open-weights/releases) for details on each version.

---

## 📑 Table of Contents

- **Prologue:** The Day Everyone Said It Was Open
- **Chapter 1:** Six Months Had Become Three
- **Chapter 2:** Who Measured That Number?
- **Chapter 3:** The Open Door That Weighs 1.7 Terabytes
- **Chapter 4:** Release Without a License
- **Chapter 5:** The Day Intelligence Stopped Being the Product
- **Chapter 6:** Distillation: An Allegation Not Yet Proven
- **Chapter 7:** There Is an Outside to the Review System
- **Chapter 8:** The Day Openness Became the Language of the State
- **Final Chapter:** Beyond Privileged Open

---

## 🔗 Related Projects

This book is part of an interconnected ecosystem of open-source projects.

| Project | Description | Link |
| --- | --- | --- |
| **The AI Strategist**               | Defining the AI Strategist role with practical frameworks for the BTC intersection                              | [GitHub](https://github.com/Leading-AI-IO/the-ai-strategist)              |
| **Depth & Velocity**                | A methodology for new business development in the generative AI era                                             | [GitHub](https://github.com/Leading-AI-IO/depth-and-velocity)             |
| **The Silence of Intelligence**     | Systematizing Anthropic CEO Dario Amodei's philosophy — Industry Anatomy Series #2                              | [GitHub](https://github.com/Leading-AI-IO/the-silence-of-intelligence)    |
| **The Anatomy of Anthropic**        | A comprehensive dissection of Anthropic's strategy, products, research, and safety                              | [GitHub](https://github.com/Leading-AI-IO/the-anatomy-of-anthropic)       |
| **The Palantir Impact**             | Dissecting Palantir Foundry's ontology strategy — Industry Anatomy Series #1                                    | [GitHub](https://github.com/Leading-AI-IO/palantir-ontology-strategy)     |
| **What They Won't Teach You**       | What the AI-advantaged generation won't teach you about AI and the "Thinking OS"                                | [GitHub](https://github.com/Leading-AI-IO/what-they-wont-teach-you)       |
| **The Edge of Intelligence**        | When AI runs on your device: the end of cloud, the beginning of edge                                            | [GitHub](https://github.com/Leading-AI-IO/edge-ai-intelligence)           |
| **The Redesign of Design Strategy** | Redefining design strategy, including a structural analysis of IDEO's decline                                   | [GitHub](https://github.com/Leading-AI-IO/design-strategy-in-the-ai-era)  |
| **The Orchestrator**                | The first-ever definition of the rarest role in the AI era                                                      | [GitHub](https://github.com/Leading-AI-IO/the-orchestrator-in-the-ai-era) |
| **Advertising, Redesigned**         | An open-source book exploring the future of advertising in the AI era through strategic analysis of 7 companies | [GitHub](https://github.com/Leading-AI-IO/advertising-redesigned)         |
| **The AI Organization**             | The root cause of AI failure is not technology. Organizational theory for the AI era                            | [GitHub](https://github.com/Leading-AI-IO/the-ai-organization)  |
| **The Structural Shift from SaaS**  | SaaS Is Dead: The Structural Shift from SaaS to Service-as-a-Software                                           | [GitHub](https://github.com/Leading-AI-IO/saas-is-dead-the-next-ai-business-model)  |
| **The 10:80:10 Principle**          | The optimal balance for human-AI synergy:「10:80:10」in the AI era.                                             | [GitHub](https://github.com/Leading-AI-IO/the-10-80-10-principle)  |
| **A Trillion Dollars and a Firebomb** | The Parallel Realities of the AI Era | [GitHub](https://github.com/Leading-AI-IO/a-trillion-and-a-firebomb) |
| **The End of the Attention Economy** | The End of the Attention Economy. What Should the Next SNS Look Like? | [GitHub](https://github.com/Leading-AI-IO/the-attention-economy-is-over)  |
| **The Growth Engine of Anthropic** | Decoding the $1T Trajectory | [GitHub](https://github.com/Leading-AI-IO/the-growth-engine-of-anthropic)  |
| **The Agentic Commerce Economy** | When AI Agents Buy, the Advertising Model Paradigm Shift | [GitHub](https://github.com/Leading-AI-IO/agentic-commerce-economy)  |
| **Will ai break the planet** | The AI Infrastructure Boom and the Race Against the Climate's Point of No Return | [GitHub](https://github.com/Leading-AI-IO/will-ai-break-the-planet)  |
| **The-forward-deployed-shift** | The Forward Deployed Shift — Where Value Survives When "Building" Is Over | [GitHub](https://github.com/Leading-AI-IO/the-forward-deployed-shift)  |
| **Earned-ai-model-optionality** | AI Models Are Switchable. But Only for Companies That Made Them So | [GitHub](https://github.com/Leading-AI-IO/earned-ai-model-optionality)  |

---

## 👤 Author

**Satoshi Yamauchi** (山内 怜史)<br>

* **AI Strategist & Business Designer at Sun Asterisk Inc.**

* **Founder / AI Strategist at [Leading.AI](https://www.leading-ai.io/)**

* Over 15 years of experience spanning Business, Technology, and Creative domains. Led 40+ projects as PL/PM at Future Architect (IT consulting), then drove business strategy and new business development at Recruit. Currently at Sun Asterisk as a Business Designer and AI Strategist, where he developed “Depth & Velocity”—a methodology for new business development powered by generative AI.

* This project is part of the research by Leading.AI.

* [📒 Read my insights on Note](https://note.com/satoshi_yamauchi)

* [🌐 Visit Leading.AI Official Website](https://www.leading-ai.io/)

---

## 🤝 Contributing

Issues and Pull Requests are welcome. Contributions are appreciated, including feedback on the book's structural analysis; new primary sources and current information on open-weight models, AI evaluation, inference infrastructure, licensing, AI regulation, and geopolitics; corrections; and translations.

---

## 📝 License

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).<br>
© 2026 Satoshi Yamauchi / [Leading AI](https://www.leading-ai.io/) — Licensed under CC BY 4.0
