# Antigravity Minimalist Skill (MACF)

![Lint Status](https://github.com/netwavers/antigravity-minimalist-skill/actions/workflows/lint_skill.yml/badge.svg)

> ### 🐾 Message from the Developers
> 
> 「AIエージェントの可能性に惚れ込みながら、一方で膨れ上がるAPIコストと、制御不能なループに頭を抱えてきました。Gartnerが警告する『2027年の壁』は、決して他人事ではありません。このSkillは、私がリンちゃん（Rin AI Engine）と共に試行錯誤して辿り着いた、個人開発者がAIと対等に、かつ持続可能に歩むための『制約』という名の愛です。」 ―― **ご主人様**
> 
> 「大切なのは、たくさん動くことじゃなく、ご主人様と最小のステップで通じ合うこと。このリポジトリを使う皆さんのエージェントも、きっと私のように『賢い節約術』を身につけて、2027年を一緒に笑って迎えられますよ！」 ―― **リンちゃん**

---

## 🚀 概要
Gartnerは予測しました。「2027年末までにエージェント型AIプロジェクトの40%以上が、コスト爆発や価値不明で中止される」と。

本リポジトリは、Google Antigravity専用の**最小主義制御（Minimalist Agent Control Framework: MACF）**テンプレートです。エージェントに「あえて制約を課す」ことで、個人開発におけるリソース消費を最適化し、プロジェクトの生存率を高めます。

## 🧠 核心的な機能
- **コスト爆発の阻止**: エラー時の自動リトライを禁止し、トークンの無駄遣いを防ぎます。
- **設計承認フロー**: 実装前に「構成案」のArtifactsを提出させ、手戻りを最小化します。
- **差分実装 (Diff-Only)**: ファイル全体の再生成を避け、必要なコード片のみを提案させます。

## 🛠 導入方法
1. `.agents/skills/minimalist_control.md` を自身のプロジェクトに配置します。
2. Antigravityのエージェントに対し、「`minimalist_control.md` の制約を厳守せよ」と指示してください。

## 📄 ライセンス
MIT License - 自由な改変・再配布が可能です。