# 【AI イノベーション室】（勝手に）週間ニュース #9 6 月 27 日～ 7 月 04 日

7 月に入り、夏本番を迎えた週となりました。今週も AI 業界では重要な発表や新たな動きが続々と登場しています。暑い日が続きますが、AI 技術の発展はますます活発になっています！ 🌟

## 【PICK UP】

- Anthropic、経済未来プログラムを発表
  - AI 技術が経済に与える影響を研究し、政策立案に活用する新しいプログラムを開始。AI 導入における社会的影響を包括的に分析し、未来の経済モデルを提案します。 🏢
  - https://www.anthropic.com/news/introducing-the-anthropic-economic-futures-program

## 最新技術動向・リリース情報

- Sakana AI、複数 LLM を協調させる「AB-MCTS」を発表

  - 推論時に複数の言語モデルを協調させる新手法を開発。一般的な推論タスクで 30%以上の精度向上を実現。 🚀
  - https://ledge.ai/articles/sakana_ai_abmcts_multi_llm

- DeepL、翻訳 AI「v1 モデル」の精度向上を発表

  - 多言語対応の精度を大幅に向上させた新モデルを発表。翻訳品質とスピードの両面で改善を実現。 🌍
  - https://www.itmedia.co.jp/aiplus/articles/2507/03/news065.html

- Meta、AI 動画編集機能の提供を開始
  - 10 秒の動画を誰でも簡単に編集できる新機能をリリース。直感的な操作でプロ品質の動画制作が可能に。 🎬
  - https://aismiley.co.jp/ai_news/meta-ai-edits-movie/

## ビジネス活用事例・実践情報

- NTT コミュニケーションズ、業務特化型 AI エージェント 20 種を提供

  - 各業界に特化した 20 種類の AI エージェントによるソリューションを開始。業務効率化と専門性を両立。 💼
  - https://aismiley.co.jp/ai_news/ntt-ai-agent-solution/

- 静岡市、衛星データと AI で水道 DX ソリューション導入

  - 衛星データと AI 技術を組み合わせて水道インフラの効率化を実現。地方自治体の DX 推進事例として注目。 🌊
  - https://aismiley.co.jp/ai_news/shizuoka-tenchijin-ai-compass/

- Salesforce AI、顧客対応で 93%の正確性を達成
  - AI 技術を活用した顧客サービスで高い精度を実現。人間レベルの対応品質を自動化で提供。 📞
  - https://www.businessinsider.jp/article/2507-marc-benioff-says-ai-working-with-93-accuracy-customer-service/

## 規制・倫理・ガバナンス

- デンマーク政府、ディープフェイク規制に向け著作権法改正へ

  - 個人の身体、顔、声に対する権利を保護する著作権法改正を計画。ディープフェイク対策の先進事例。 ⚖️
  - https://ledge.ai/articles/denmark_ai_deepfake_copyright_law

- 韓国、AI 強国を目指す 100 兆ウォンプロジェクト始動

  - 李在明政権が大規模な AI 投資プロジェクトを開始。国家戦略として AI 技術の発展を推進。 🇰🇷
  - https://www.afpbb.com/articles/-/3586853

- 中国、18 か月で 100 以上の AI 技術革新を計画
  - 政府主導で大規模な AI 技術開発プロジェクトを推進。技術競争力の向上を目指す包括的な取り組み。 🇨🇳
  - https://www.afpbb.com/articles/-/3585977

## 生成 AI 市場の展望

今週は大手企業による実用的な AI 導入事例が多数発表され、AI 技術の社会実装が加速していることが確認できました。特に業務特化型 AI エージェントや顧客対応 AI の高精度化は、ビジネス現場での実用性を大きく向上させています。 📊

編集：AI イノベーション室(by LLM: Claude Opus 4)

---

## プロンプト

- 差分
  - https://github.com/naoto24kawa/generate_weekly_ai_news_prompt/commit/4e388cbfee00a29224af70894f637ff66c5e0632
- 改善点
  - `Bash(gemini -p:*)`をクビにしました
    - まだまだ生成 AI はトレンドの検索が下手です
- 改善したい点
  - データソースは固定で開き直ることにします
    - まだリンクが上手く取れてなかったりするので情報収集に関するプロンプトを改善したい
