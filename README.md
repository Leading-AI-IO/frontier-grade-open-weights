# Frontier-Grade Open Weights

**フロンティア級のオープンウェイトモデルは、開かれたのか / They Matched the Frontier. But No One Can Hold Them.**

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Language](https://img.shields.io/badge/Language-Japanese%20%7C%20English-blue)](docs/)

<p align="left">
  <img src="./assets/ogp_design.png" width="80%">
</p>

*Read this in other languages: [English](README_en.md)*

---

## 📖 概要

2026年7月17日、中国のMoonshot AIは、2.8兆パラメータの「Kimi K3」を発表した。独立評価では世界の最先端モデルに迫り、フロントエンド・コーディングでは首位に立った。市場はこれを、オープンウェイトがフロンティアへ到達した瞬間として受け止めた。だが発表時点で、その重みはまだ公開されていなかった。

本書が捉えるのは、単純な「オープン対クローズド」の競争ではない。重みが公開されても、2.8兆パラメータを保持し、64基以上のアクセラレータで動かし、独立検証し、商用利用できる主体は限られる。**公開されているが、到達できない。** 本書はこの状態を、**「特権的なオープン（Privileged Open）」**と名づける。

本書は、オープンウェイトとクローズドモデルの性能差、自己申告ベンチマークと独立測定の境界、巨大モデルを阻む物理・制度・証拠・規制の壁、AIラボの収益構造、蒸留をめぐる未検証の告発、米中欧の政策、そして中国製オープンモデルへ移動する開発者エコシステムを、一次資料と独立データから構造的に検証する。

中心命題は一つである。**移動したのは、モデルの所有権ではない。希少性の在処である。** 賢さがコモディティ化するほど、企業固有の業務文脈、一次情報、運用能力、検証する判断力が希少になる。本書は、フロンティアが開かれながら、なお「オープン」にはなっていない世界で、何が価値を持ち、誰が勝つのかを問うOSS書籍である。

---

## 📄 ドキュメント

| ファイル | 言語 | 内容 |
| --- | --- | --- |
| [frontier-grade-open-weights_JP.md](./docs/jp/frontier-grade-open-weights_JP.md) | 🇯🇵 日本語 | 本文（日本語版） |
| [frontier-grade-open-weights_EN.md](./docs/en/frontier-grade-open-weights_EN.md) | 🇺🇸 English | 本文（英語版） |

---

## 📑 目次

- **序章:** 開かれた、と誰もが言った日
- **第1章:** 6ヶ月は、3ヶ月になっていた
- **第2章:** その数字は、誰が測ったのか
- **第3章:** 1.7テラバイトの、開かれた扉
- **第4章:** ライセンスなき公開
- **第5章:** 賢さが売り物でなくなった日
- **第6章:** 蒸留という、証明されていない告発
- **第7章:** 審査には、外側がある
- **第8章:** 開放が、国家の言葉になった日
- **終章:** 特権的なオープンの、その先へ

---

## 🔗 Related Projects

本書は、以下のOSSプロジェクトと相互に接続されている。

| プロジェクト | 概要 | リンク |
| --- | --- | --- |
| **The AI Strategist**               | AIストラテジストという職業を定義し、BTC交差点で戦うための実践的フレームワーク    | [GitHub](https://github.com/Leading-AI-IO/the-ai-strategist)              |
| **Depth & Velocity**                | 生成AI時代の新規事業開発方法論                             | [GitHub](https://github.com/Leading-AI-IO/depth-and-velocity)             |
| **The Silence of Intelligence**     | Anthropic CEO ダリオ・アモディの思想を体系化。産業構造の解剖シリーズ第2弾 | [GitHub](https://github.com/Leading-AI-IO/the-silence-of-intelligence)    |
| **The Anatomy of Anthropic**        | Anthropicの戦略・製品・研究・安全性を包括的に解剖                | [GitHub](https://github.com/Leading-AI-IO/the-anatomy-of-anthropic)       |
| **The Palantir Impact**             | Palantir Foundryのオントロジー戦略を解剖。産業構造の解剖シリーズ第1弾  | [GitHub](https://github.com/Leading-AI-IO/palantir-ontology-strategy)     |
| **What They Won't Teach You**       | AIに有利な世代が教えない、AIの使い方と"思考のOS"                 | [GitHub](https://github.com/Leading-AI-IO/what-they-wont-teach-you)       |
| **The Edge of Intelligence**        | AIがあなたのデバイスで動く時代：クラウドの終わりと、エッジの始まり           | [GitHub](https://github.com/Leading-AI-IO/edge-ai-intelligence)           |
| **The Redesign of Design Strategy** | デザイン戦略の再定義。IDEO崩壊の構造分析を含む                    | [GitHub](https://github.com/Leading-AI-IO/design-strategy-in-the-ai-era)  |
| **The Orchestrator**                | AI時代に最も希少な人材像「オーケストレーター」を世界で初めて定義            | [GitHub](https://github.com/Leading-AI-IO/the-orchestrator-in-the-ai-era) |
| **Advertising, Redesigned**         | AI時代の広告の未来を、7社の戦略と構造分析から描くOSS書籍              | [GitHub](https://github.com/Leading-AI-IO/advertising-redesigned)         |
| **The AI Organization**             | AI導入が失敗する本質は技術ではなく組織にある。AI時代の組織論      | [GitHub](https://github.com/Leading-AI-IO/the-ai-organization)  |
| **The Structural Shift from SaaS**  | SaaSからService-as-a-Softwareへの構造的転換。Next SaaS ビジネスモデル。      | [GitHub](https://github.com/Leading-AI-IO/saas-is-dead-the-next-ai-business-model)  |
| **The 10:80:10 Principle**          | 人とAIの共創黄金比「10:80:10」の法則——AI時代の思考のOS。      | [GitHub](https://github.com/Leading-AI-IO/the-10-80-10-principle)  |
| **A Trillion Dollars and a Firebomb** | 1兆ドルと火炎瓶。AI時代の同時加速する現実。 | [GitHub](https://github.com/Leading-AI-IO/a-trillion-and-a-firebomb)  |
| **The End of the Attention Economy** | アテンション・エコノミーの終わり。次世代SNSの在り方とは？ | [GitHub](https://github.com/Leading-AI-IO/the-attention-economy-is-over)  |
| **The Growth Engine of Anthropic** | Anthropicの1兆ドル到達の構造解剖。 | [GitHub](https://github.com/Leading-AI-IO/the-growth-engine-of-anthropic)  |
| **The Agentic Commerce Economy** | AIエージェントが購買を代行する時代、広告モデルの構造的変化。 | [GitHub](https://github.com/Leading-AI-IO/agentic-commerce-economy)  |
| **Will ai break the planet** | 数十兆円のインフラ投資と、地球温暖化の「不可逆ライン」。 | [GitHub](https://github.com/Leading-AI-IO/will-ai-break-the-planet)  |
| **The-forward-deployed-shift** | 成果実装 ── FDEが示す、AIで「作る」が終わった世界の価値のありか。 | [GitHub](https://github.com/Leading-AI-IO/the-forward-deployed-shift)  |

---

## 👤 著者

**Satoshi Yamauchi** (山内 怜史)

* **AI Strategist & Business Designer at Sun Asterisk Inc.**

* **Founder / AI Strategist at [Leading.AI](https://www.leading-ai.io/)**

* 15年以上にわたりBusiness・Technology・Creativeの3領域を越境。フューチャーアーキテクトでITコンサルタントとして40案件のPL/PMを推進後、リクルートで事業戦略・新規事業開発に従事。Sun Asteriskでビジネスデザイナー兼AIストラテジストとして、新規事業×生成AIの方法論「Depth & Velocity」を体系化。

* This project is part of the research by Leading.AI.

* [📒 Read my insights on Note](https://note.com/satoshi_yamauchi)

* [🌐 Visit Leading.AI Official Website](https://www.leading-ai.io/)

---

## 🤝 Contributing

Issues and Pull Requests are welcome. 本書の構造分析に対するフィードバック、オープンウェイトモデル・AI評価・推論インフラ・ライセンス・AI規制・地政学に関する最新情報、一次資料の追加、誤字脱字の修正、翻訳へのContributeを歓迎します。

---

## 📝 License

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).<br>
© 2026 Satoshi Yamauchi / [Leading AI](https://www.leading-ai.io/) — Licensed under CC BY 4.0
