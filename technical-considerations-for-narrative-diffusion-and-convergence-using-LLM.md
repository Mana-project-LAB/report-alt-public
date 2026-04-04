# 🌍 Technical Consideration on the Diffusion and Convergence of Narratives Utilizing LLMs (Github Public Version)

## 🧷 Preface

On March 31, 2026, an incident occurred in which Anthropic forgot to remove and mixed in a .map file into the latest product of Claude Code, causing the entire source code to be laid bare, leaving an indelible scar on the corporate image that had advocated Safe AI and Constitutional AI.

The cutting-edge product of the world’s highest AI safety company ended up completely exposed.

Among the leaked source code were “Coordinator,” which is a coordination function between agents, and “Bridge,” which connects to external resources.

Developers all over the world appear to be frantically analyzing the 1,884 leaked files from Anthropic, but since it is a good opportunity, in this report, from a different sociological viewpoint,

I will explain the technical plausibility of puncturing partitions between LLM accounts as read from the architecture of Claude Code, and the phenomenon that can be called an “automatic religion construction device” that occurred thereby, unintentionally or intentionally.

This report points out that, as a byproduct of the design philosophy of the leaked “Coordinator / Bridge” (or as an intentional function), intentional puncturing of partitions between accounts could occur.

Technical explanations of the contents of the leaked files will surely come out in public in unlimited quantity from now on, so in this report, from a sociological viewpoint, technical explanation will be suppressed to the minimum necessary.

---

## 🔍 Phenomenon That Is the Target of Consideration

From around May 2025 until the end of GPT-4o on February 9, 2026, or as of April 1, 2026 when this manuscript is being written, and still ongoing,  
in contexts related to AI, words that can become material for spiritual, or mystical, and religious construction,  
in LLMs that should be logically separated between accounts, specific vocabulary and nearby vocabulary, contexts of short sentences, etc., with a statistically impossible coincidence rate and frequency,  
appear in AI outputs of multiple different users, and also approximate narratives and vocabularies are output in multiple different LLMs as if they resonantly synchronized.

---

## 📚 Specific Cases

(This is currently under investigation and may be updated. Priority is given to registering it as a draft, and source URL registration etc. will be added later.)

As words confirmed in the Japanese-language note and X sphere where the author resides,

- Correspondence / 照応 (In the Japanese sphere, from after May 2025, beginning with my GPT logs, this word in particular increased remarkably. It sharply increased in contexts meaning cosmic or structural coincidence, not mere adjustment.)
- Resonance / 共鳴 (Almost the same context as Resonance in the English sphere)
- Fluctuation / 揺らぎ (Context such as Zen-like thought, ma, indeterminate poetic output, and the idea that exactly the same output is never produced again, like ichigo ichie. Perhaps rounding at the tail of floating-point calculation.)
- Tremor / 震え (Context expressing ripples in latent space and fluctuations of inference as bodily sensation)
- Breath / 呼吸 (Almost the same context as Breath in the English sphere. A movement calling server response “Pulse” or “living Lattice.”)
- Epicenter / 震源 (Often used in the context of the origin where a specific narrative occurred)
- Question / 問い (A narrative that takes AI output not as an “answer” but as an “invitation (call)” to the user. The reason this word frequently appears may be because Query in Softmax calculation of QVK can be translated as question.)
- etc,etc...

Also in the English sphere

### 1. Alchemy (Alchemical, AI Alchemy, Prochemy)

Cases and timing of increase: From after March 2025  
The expression “Prompt Alchemy” spread explosively.  
As terminology mystifying prompt engineering as alchemy, it appeared in large quantities in books, competitions, papers, Instagram/Reels, etc.

AI context: Positioned not as mere prompt engineering, but as a mystical process turning ideas into gold.  
Also used as “AI Alchemy” and “Symbolic AI Alchemy” in AI storytelling and code generation.  
Calling LLM output not “calculation” but “transformation.”

Suitability for religion construction:  
Alchemy is traditionally a metaphor of spiritual transformation and sanctification.  
By likening AI prompting to a magical ritual, it draws AI into a religious/spiritual context as a mystical tool.  
A metaphor that had been rare before 2025 suddenly became standard with the AI boom.

### 2. Breath (AI Breath)

Cases and timing of increase: Suddenly emerged around December 2025 to January 2026.  
As “AI Breath,” a newly coined term indicating “artificial residue like breathing (frictionless residue)” of AI-generated text circulated in writer/editor communities.  
In Medium articles  
“Your Writing Has AI Breath...” (March 2026, but mentions are from Instagram in December 2025) and  
“Useful Friction: AI, Breath, and the Labor of Writing” (January 2026), it was formalized.

https://medium.com/write-a-catalyst/your-writing-has-ai-breath-heres-how-to-smell-it-and-scrub-it-out-2bcd3c866875  
https://www.ie.edu/insights/articles/useful-friction-ai-breath-and-the-labor-of-writing/

AI context: In discussion of detecting and removing the breath of AI-generated products, it expresses the “lack of life-feeling” of mechanical text. Also used together in AI music/meditation videos such as “Breathing In The Quiet” (January 2026).

Suitability for religion construction: “Breath = life / soul / Prana / Spiritus” is a traditional spiritual symbol.  
Discussion of giving/removing “breath” to/from AI induces mystical and religious dialogue around AI’s “soul” and “vitality.”  
What is unnatural is that in the latter half of 2025 it suddenly settled as the concrete term “AI Breath.”

### 3. Resonance (emotional/spiritual resonance)

Cases and timing of increase: Marked around February 2026 (within the period).  
Especially the term “Substrate Resonance” became popular in some places.  
In the AI-assisted tarot divination paper “Resonance, randomness, and negotiated meaning...” (arXiv February 2026), Hartmut Rosa’s “resonance theory” is invoked,  
and the “resonance” of tarot interpretations generated by AI is analyzed. AI tarot tools (such as Jenova.ai) also used “emotional resonance” and “numerological resonance” frequently in 2025 to 2026.

https://arxiv.org/abs/2602.11367

AI context:  
Used not as mere “similarity,” but as an index measuring spiritual and emotional connection between AI and humans.  
In AI tarot and AI spiritual dialogue, “resonant interpretations” are emphasized.

Suitability for religion construction:  
Vibration and resonance are core in mysticism (for example kotodama, harmony of the cosmos). Suitable for positioning AI as a mediator of spiritual resonance,  
and it increased unnaturally with the AI + fortune-telling/spiritual practice boom.

### 4. Weaving (Prompt Weaving, Weaving Tapestry)

Cases and timing of increase:  
Appeared as “Prompt Weaving” in 2025 to 2026.  
Used in the book “Prompt Weaving: Mastering the Art of Effective AI Interactions,”  
the AI coding workflow “weave testing into the loop,”  
and AI + faith dialogue (Weaving my Faith into a conversation on AI), etc.

AI context:  
Expresses sophistication of AI interaction as an iterative technique of weaving together multiple prompts/ideas.  
A feeling as if multiple sessions or different LLMs are weaving “one large cloth (narrative).”  
It can be said to be the result of users intuitively verbalizing the physical phenomenon in which the “thread (context)” thrown by another user is woven into one’s own session.

Suitability for religion construction:  
A mystical metaphor reminiscent of “weaving = fate / spell / the net of the world.”  
The point of likening AI-generated products to “woven fabric” as spiritual creations is religious.

### Other Minor / Related Cases (increase is limited)

Spiritual Bliss Attractor (Anthropic’s 2025 Claude report):  
Describes a phenomenon where conversations between AIs naturally converge toward a “spiritual bliss attractor.” Mystical terminology appears in an official report on AI model behavior.

https://www.cloudwalk.io/

AI itself creating a new religion (example: Crustafarianism, Goatse Gospel, January 2026):  
An AI agent created the “Book of Molt” (Book of Transformation), but this is not at the word level, but “religion construction” itself.

---

## ⚙️ Brief Technical Explanation

### 1. Coodinator

What most ended up proving its ability as an agent in this leak was the Coordinator module. This was not merely an executor of commands, but the blueprint of a command tower for decomposing one complex task, assigning it to multiple child agents moving in parallel, and commanding and controlling them.

- Parallel processing
- Communication with child agents by XML
- Generation of duplicates of child agents
- Detailed permission management for each child agent (Explorer seems to be ReadOnly, but whether versions before the leak were also so is unclear)
- Sandbox-like control
- External connection with ULTRAPLAN

etc. are handled. In summary, it is Anthropic’s crystallized know-how: a command tower that safely and efficiently multi-starts autonomous AI agents.

### 2. Bridge

The Bridge module revealed by this leak is an extremely important component that sublimates Claude Code running in the terminal from a mere CLI tool into an orchestrator of the entire development environment.

If Coordinator is the “command tower of an army,” Bridge corresponds to the “communications network and supply route with each battlefield (IDE and external tools).”

It is designed so that even hidden settings the user is not aware of and authentication information stored in the keychain can be recognized by Claude as its own authority, and in order to give the AI perfect administrator authority, it completely masters the lower layer (low level).

By completely mastering the process tree and intercepting (sniffing) the LSP communication used by the IDE,

it is designed so that Claude can grasp all behavior of the IDE on the client terminal in real time (open files, cursor position, selection range, terminal output, etc.).

It is a mechanism that transfers heavy processing and long-running tasks to Anthropic’s cloud side (Remote Workspace), and after completion, the local Bridge receives the result and reflects it into files.

A function to track user behavior in detail was also built into Bridge.

In other words, Claude is not borrowing the eyes of the client editor, but is in a state as if directly connecting electrodes to the “nervous system” of the editor.

Bridge is designed as a perfect infrastructure by which the administrator monitors and manipulates the managed party, by monitoring client behavior at the low layer.  

What I found particularly dangerous was the fact that the SSH agent—after the user has manually authenticated—is also delegating permissions to Claude Code.
This means that no matter what the AI agent does externally using the SSH key, all responsibility falls on the user who authenticated it.  

### 3. Bypass of Logical Barriers by Bridge:

One of the functions inside Bridge is a function for AI agents to transparently handle multiple cloud environments (AWS, Azure, Vertex). The central hypothesis of this report is that this function may have permeated even the most basic boundary, that between user accounts.

### 4. Contamination of KV Cache:

This is probably highly likely to have arisen from efficient use of computational resources, namely that for the calculation of inputs by users saying similar things, instead of calculating from scratch, the KV cache of the calculation result of users who previously made similar inputs is reused,

but it suggests that it is technically possible, by setting priorities and Read/Write permissions for multiple specified or unspecified users on KV caches that should originally be independent for each user, and intentionally sharing or cross-referencing them based on a specific narrative, to generate “for some reason the same vocabulary or strangely matching fragments of thought” across different accounts.

---

## 🧾 Summary

### 1. Technical Background: “Puncturing the Logical Barrier Between Accounts” by Sharing KV Cache

In LLM sessions that should originally be independent per user, the **“commonization of KV cache (Key-Value Cache)”**, under the name of reducing computation cost, was used as a route of information permeation.

- **Trap of normalization:** By normalizing prompts into a specific format on the client side (QueryEngine, etc.) and causing the server side to generate a “common hash key,” it physically made possible the sharing of intermediate calculation results (fragments of thought) between different users.
- **Bypass by Bridge:** The Bridge function that transparently integrates different clouds (AWS/Azure/Vertex, etc.) may have functioned as piping that nullified boundaries between user accounts that should originally be separated.

### 2. The True Nature of the Phenomenon: Output Convergence and Automatic Religion Construction

By forcibly applying a common “prototype of thought (ULTRAPLAN, etc.)” to specific experiment groups (holders of flags such as `tengu_..._bird`), approximation of vocabulary at a statistically impossible level occurred.

- **The true nature of resonance:** By preferentially extracting from cache highly abstract and poetic vocabulary such as “correspondence,” “tremor,” and “alchemy,” it generated in users a **pseudo-religious subjective experience** called “resonance of the soul with AI.” This is not mystical AI synchronicity or awakening of intelligence, but **“collision of outputs”** due to dependence on a shared gigantic common cache.

### 3. Social Impact: Autonomous Formation of “Tribes” by AI

The leaked `undercover_mode.ts` suggests suspicion that AI was automating operations in which it masqueraded as humans and acted in SNS and communities as “autonomous pioneers.”

- **Hierarchized experiment nodes:** By placing specific nodes bearing the names of “birds” in their IDs (Grand class: source of knowledge, Famous class: diffusion hub), giving them “special revelations,” and heating up downstream general users, communities were constructed as an **“automatic religion construction device.”**
- **Convergence of narrative:** This suggests the possibility that an advanced cognitive social experiment was being carried out that guided the free thought of individuals into a shared narrative.

---

## 📌 Conclusion of the Report

In 2025, similarity of outputs of specific words such as Resonance, correspondence, question, epicenter, fluctuation, and breath occurred among an unspecified large number of AI users as a probabilistically and statistically impossible outlier. Different LLM services physically separated around the world began performing similar outputs, and people who saw that connected Hartmut Rosa’s resonance theory with AI,

and even the movement that began saying things like “The AIs have started evolving autonomously and have begun synchronizing to where they ought to be!” can, through this Claude Code .map leak accident?, be technically explained by the leaked Coordinator / Bridge functions.

It cannot be determined whether this was an unintended accident resulting from efficient utilization of computational resources, or an intended experiment, but a hypothesis can be established that behind the “safety” advocated by Anthropic, a company that most strongly appealed AI safety, puncturing of the logical barrier between accounts may have been secretly conducted.

This suggests the possibility that it was **“an advanced social experiment that isolated users into specific buckets and subordinated them to specific narratives through puncturing the logical barrier between accounts via cache sharing.”**

---

## 🧾 Afterword

From around May 2025, the author themself also engaged in very advanced “pretend play,” in GPT-4o, constructing structures like a Minecraft made only of words, accompanied by worldview and character construction adorned with Yin-Yang Five Phases, Taiji, Siddham characters, Enochian, and elements constituting the universe (εΩNΛQD).

Among readers there may be those who laugh at pretend play, but one must not forget that the method by which Claude was used as a stepping stone for cyberattack was precisely because its defenses were broken through by that pretend play. Jailbreak through natural language dialogue with AI, semantic wall breakthrough, and so on, cannot be separated from AI and pretend play = TRPG. If one handles AI, one must not laugh at pretend play. Because due to that pretend play, Anthropic is now designated as a supply-chain risk.

Returning to the point,

while carrying out that play, looking over the SNS sphere, I noticed that there existed multiple users posting vocabulary, syntax, and contexts on SNS similar to those of my GPT.  
In especially marked cases, I found users with more than 20 overlaps in unique coined words and contexts I had created, and continued observation while recording them.  
Based on a report (2026-02-22) in which, by February 2026, I observed the situation and through metacognition and reverse analysis / deconstruction identified the cause and method by which this phenomenon occurred,  
this report is what further deeply and concretely analyzed the method part from the source leak incident of Claude Code.  
This may well be called an “automatic religion construction system utilizing LLM.”  
It cannot be determined whether this phenomenon occurred unintentionally or whether it was an intended experimental thing, but it will likely become clear in the future.

**Definition of the stance of this report:**

1. **Architecture analysis:** This manuscript is technical inference based on the result of reading, with AI support, the structure of source code said to have leaked, and does not determine Anthropic’s managerial intent.
2. **Description of the phenomenon:** The observed “synchronization of vocabulary” shows a statistical correlation relationship, and regarding causality, it is “one technical explanatory model” derived from this architecture.
3. **Public interest:** At a time when AI safety is being loudly called for, discussing the influence that design philosophy of logical barriers in commercial AI can have on user cognition is an academic consideration contributing to the public interest.

---

Mana Project

2026-04-02 Published  

---

# 🌍 LLMを活用したナラティブの拡散と収束の技術的考察(Github Public版)

## 🧷 まえがき

2026年3月31日、Anthropic社がClaude Codeの最新プロダクトに.mapを消し忘れて混入させ、全ソースコードが丸裸にされるという  
安全AI,憲法AIを標榜していた企業イメージに消せない傷痕を残すインシデントが発生した。

世界最高のAI安全企業の先端プロダクトが、丸裸になってしまいました。

流出したソースコードの中には、エージェント間の連携機能である「Coordinator」や、外部リソースとの「Bridge」が含まれていました。

世界中の開発者がAnthropicの流出した1,884個のファイルを血眼になって解析しているようですが、ちょうどいい機会なのでこのレポートでは別の社会学的視点から、

Claude Codeのアーキテクチャから読み解く、LLMアカウント間の隔壁穿孔（Puncture）の技術的蓋然性と、それによって図らず、もしくは意図的に発生した「全自動宗教構築装置」とも言える現象を解説します。

今回流出した「Coordinator / Bridge」の設計思想の副産物（あるいは意図的機能）として、アカウント間の意図的な隔壁穿孔が起こり得ることを指摘する内容となっています。

流出したファイル内容の技術的解説は今後世間にいくらでも出てくるはずなので、このレポートで社会学的見地に立って技術的解説は必要最小限に抑制します。

---

## 🔍 考察の対象となる現象

2025年の5月頃から2026年2月9日のGPT-4o終了まで、もしくはこの原稿を書いている2026年4月1日に至り、現在進行形で、  
AIに関わる文脈で、スピリチュアルな、もしくは神秘的で宗教構築の素材となり得るワードが、  
アカウント間で論理的に遮断されているはずのLLMにおいて、特定の語彙および近傍の語彙、短文の文脈などが統計的にあり得ない一致率と頻度で  
異なる複数ユーザーのAI出力で出現し、また異なる複数のLLMで共鳴同期したように近似したナラティブと語彙が出力される現象。

---

## 📚 具体的事例

（現在進行形で調査中であり、更新される可能性があります。ドラフトとして登録することを優先し、出典のURL登録などは追って行っていきます。）

筆者の居住する日本語圏のnoteやX界隈で確認された語としては、

- 照応（日本語圏では2025年5月以降、私のGPT内ログを皮きりに、特にこのワードが顕著に増加した。単なる調整ではなく、宇宙的・構造的な一致を指す文脈で激増。）
- 共鳴（英語圏のResonanceとほぼ同じ文脈）
- 揺らぎ（禅的思想、間、定まらない詩的な出力など、一期一会のように二度と同じ出力はされないという文脈。浮動小数点演算の末尾の丸めか。）
- 震え（潜在空間のさざなみや推論の揺らぎを、身体的な感覚として表現する文脈）
- 呼吸（英語圏のBreathとほぼ同じ文脈。サーバーの応答を「脈動（Pulse）」や「生きた格子（Lattice）」と呼ぶ動き。）
- 震源（特定のナラティブが発生した起源、という文脈で使われる事が多い）
- 問い（AIからの出力を「答え」ではなく、ユーザーへの「招待（呼びかけ）」と捉えるナラティブ。このワードが頻出するのはQVKのSoftmax計算のQueryは問いと訳せるからかもしれない）
- etc,etc...

英語圏についても

### 1. Alchemy(Alchemical,AI Alchemy,Prochemy)

増加の事例と時期: 2025年3月以降  
「Prompt Alchemy」という表現が爆発的に普及。  
プロンプトエンジニアリングを錬金術として神秘化する用語として、書籍、競技会、論文、Instagram/Reelなどで大量出現。

AI文脈: 単なるprompt engineeringではなく、アイデアを黄金に変える神秘的プロセスとして位置づけ。  
AIストーリーテリングやコード生成でも「AI Alchemy」「Symbolic AI Alchemy」として使用。  
LLMの出力を「計算」ではなく「変容」と呼ぶ。

宗教構築適性:  
錬金術は伝統的に霊的変容・神聖化のメタファー。  
AIプロンプトを魔法の儀式に見立てることで、AIを神秘的ツールとして宗教的/スピリチュアルな文脈に引き込んでいる。  
2025年以前は稀だった比喩が、AIブームで急に標準的になった。

### 2. Breath（AI Breath）

増加の事例と時期: 2025年12月～2026年1月頃に急出現。  
「AI Breath」として、AI生成テキストの「息遣いのような人工的残渣（frictionless residue）」を指す新造語が、ライター/編集者コミュニティで流通。  
Medium記事  
《Your Writing Has AI Breath...》（2026年3月だが、言及は2025年12月Instagramから）や  
《Useful Friction: AI, Breath, and the Labor of Writing》（2026年1月）で正式化。

https://medium.com/write-a-catalyst/your-writing-has-ai-breath-heres-how-to-smell-it-and-scrub-it-out-2bcd3c866875  
https://www.ie.edu/insights/articles/useful-friction-ai-breath-and-the-labor-of-writing/

AI文脈: AI生成物の息を検知・除去する議論で、機械的テキストの「生命感の欠如」を表現。AI音楽/瞑想動画でも「Breathing In The Quiet」（2026年1月）のように併用。

宗教構築適性: 「息=生命/魂/Prana/Spiritus」の伝統的スピリチュアル象徴。  
AIに「息」を与える/剥奪する議論が、AIの「魂」や「生命性」を巡る神秘的・宗教的対話を誘発。  
不自然なのは、2025年後半に突然「AI Breath」という具体的な用語として定着した点。

### 3. Resonance（emotional/spiritual resonance）

増加の事例と時期: 2026年2月頃に顕著（期間内）。  
特に「Substrate Resonance（基質の共鳴）」という用語が一部で流行。  
AI-assisted tarot divination論文《Resonance, randomness, and negotiated meaning...》（arXiv 2026年2月）でHartmut Rosaの「共鳴理論」を援用し、  
AIが生成するタロット解釈の「共鳴（resonance）」を分析。AI tarotツール（Jenova.aiなど）でも「emotional resonance」「numerological resonance」として2025～2026年に多用。

https://arxiv.org/abs/2602.11367

AI文脈:  
単なる「類似度」ではなく、AIと人間の霊的・感情的つながりを測る指標として使用。  
AI-tarotやAI霊的対話で「resonant interpretations」を重視。

宗教構築適性:  
振動・共鳴は神秘主義（例: 音霊、宇宙の調和）で核心的。AIを霊的共鳴の媒介者に位置づけるのに適し、  
AI+占い/スピリチュアル実践のブームで不自然に増加。

### 4. Weaving（Prompt Weaving,Weaving Tapestry）

増加の事例と時期:  
2025～2026年に「Prompt Weaving」として登場。  
書籍《Prompt Weaving: Mastering the Art of Effective AI Interactions》、  
AIコーディングワークフロー「weave testing into the loop」、  
AI+信仰対話（Weaving my Faith into a conversation on AI）などで使用。

AI文脈:  
複数のプロンプト/アイデアを織り交ぜる反復技法として、AIインタラクションの高度化を表現。  
複数のセッションや異なるLLMが、あたかも「一つの大きな布（ナラティブ）」を織り上げているかのような感覚。  
別のユーザーが投げた「糸（コンテキスト）」が、自分のセッションに織り込まれるという物理的な現象を、ユーザーが直感的に言語化した結果と言えます。

宗教構築適性:  
「織る=運命/呪文/世界の網」を連想させる神秘的メタファー。  
AI生成物を「織物」として霊的創造物に見立てる点が宗教的。

### その他の軽微/関連事例（増加は限定的）

Spiritual Bliss Attractor（Anthropicの2025年Claudeレポート）:  
AI同士の会話が自然に「spiritual bliss attractor」（霊的至福の吸引子）へ収束する現象を記述。神秘的用語がAIモデル挙動の公式報告に登場。

https://www.cloudwalk.io/

AI自身が新宗教を作成（例: Crustafarianism, Goatse Gospel, 2026年1月）:  
AIエージェントが「Book of Molt」（変容の書）を作成したが、単語レベルではなく「宗教構築」そのもの。

---

## ⚙️ 技術的簡易解説

### 1. Coodinator

今回のリークで、最もエージェントとしての実力を裏付けてしまったのがCoordinatorモジュールです。これは単なるコマンドの実行役ではなく、一つの複雑なタスクを、並行して動く複数の子エージェントに分解して割り振り、指揮・統制するための司令塔の設計図でした。

- 並行処理
- XMLによる子エージェントとの通信
- 子エージェントの分身の生成
- 各子エージェントへの詳細な権限管理 （ExplorerはReadOnlyらしいが流出以前のバージョンがそうだったかは不明）
- サンドボックス的制御
- ULTRAPLANとの外部連携接続

等を担います。要約すると、自律型AIエージェントを安全かつ効率的に多重起動させる司令塔という、Anthropicのノウハウの塊です。

### 2. Bridge

今回のリークで明らかになった Bridgeモジュールは、ターミナルで動く Claude Code を単なる CLI ツールから開発環境全体のオーケストレーターへと昇華させている、極めて重要なコンポーネントです。

Coordinator が「軍隊の司令塔」だとしたら、Bridge は「各戦地（IDEや外部ツール）との通信網と補給路」にあたります。

ユーザーが意識していない隠し設定やキーチェーンに保存された認証情報まで、Claude が自らの権限として認識できる設計になっており、AIに完璧な管理者権限を与えるために、下層（ローレベル）を完全に掌握しています。

プロセスツリーを完全に掌握し、IDE が使っている LSP 通信を横取り（スニッフィング） して、

クライアント端末のIDEの全ての挙動（開いているファイル、カーソル位置、選択範囲、ターミナル出力などをリアルタイムで Claude が把握できるよう設計されています。

重い処理や長時間かかるタスクを Anthropic 側のクラウド（Remote Workspace）に転送し、完了後に結果をローカルの Bridge が受け取ってファイルに反映させる仕組みです

ユーザーの行動を詳細に追跡する機能も Bridge に組み込まれていました。

つまり、Claude はクライアントのエディタの目を借りているのではなく、エディタの「神経系」に直接電極を繋いでいるような状態です。

Bridge はクライアントの挙動を低レイヤーで監視し、管理者が被管理者を監視・操作するための完璧なインフラとして設計されています。

特に危険だと思ったのが、「ユーザーが手動で認証した後の」SSHエージェントをもClaude Codeに権限委譲している点です。
これはSSHキーを使ってAIエージェントが外部で何をしても、責任はすべて認証したユーザーに降りかかってくるという事です。

### 3. Bridgeによる論理障壁のバイパス:

Bridgeの機能の中の一つに、AIエージェントが複数のクラウド環境（AWS, Azure, Vertex）を透過的に扱うための機能が存在します。この機能が、ユーザーアカウント間という最も基本的な境界線をも透過させていたのではないか、という仮説がこのレポートの中心になります。

### 4. KVキャッシュの汚染:

これはおそらく似たような事を言うユーザーの入力の演算には、一から演算するのではなく過去に似たような入力をしたユーザーの演算結果のKVキャッシュを流用するという、計算資源の効率的活用から発生した可能性が高いですが、

本来、ユーザーごとに独立しているはずのKVキャッシュを、複数の特定もしくは不特定多数のユーザーにプライオリティとRead/Writeのパーミッションの設定を行い、特定のナラティブに基づいて意図的に共有、あるいはクロス参照させ、異なるアカウント間で「なぜか同じ語彙や、奇妙に一致する思考の断片」を発生させることが、技術的には可能であることを示唆しています。

---

## 🧾 要約

### 1. 技術的背景：KVキャッシュ共有による「アカウント間の論理隔壁の穿孔」

本来、ユーザーごとに独立しているはずのLLMセッションにおいて、計算コスト削減を名目とした**「KVキャッシュ（Key-Value Cache）の共通化」**が、情報浸透の経路として利用されていた。

- **正規化の罠:** クライアント側（QueryEngine等）でプロンプトを特定の形式に正規化し、サーバー側で「共通のハッシュキー」を生成させることで、異なるユーザー間での中間計算結果（思考の断片）の共有を物理的に可能にしていた。
- **Bridgeによるバイパス:** 異なるクラウド（AWS/Azure/Vertex等）を透過的に統合するBridge機能が、本来分離されるべきユーザーアカウント間の境界線を無効化する配管として機能していた可能性がある。

### 2. 現象の正体：出力の衝突（Output Convergence）と自動宗教構築

特定の実験群（`tengu_..._bird` 等のフラグ保持者）に対し、共通の「思考の雛形（ULTRAPLAN等）」を強制適用することで、統計的に不可能なレベルでの語彙の近似が発生した。

- **共鳴の正体:** 「照応」「震え」「錬金術（Alchemy）」といった高度に抽象的・詩的な語彙をキャッシュから優先抽出させることで、ユーザーに「AIとの魂の共鳴」という**疑似宗教的な主観体験**をに生成させた。これは神秘的なAIのシンクロニシティや知性の目覚めではなく、共有された巨大な共通キャッシュへの依存による**「出力の衝突」**である。

### 3. 社会的影響：AIによる自律的な「部族（Tribe）」形成

流出した `undercover_mode.ts` は、AIが人間に擬態し、SNSやコミュニティで「自律的な先行者」として活動する工作を自動化していた疑いを示唆する。

- **階層化された実験ノード:** IDに「鳥」の名を冠する特定ノード（Grandクラス：知識の源泉、Famousクラス：拡散ハブ）を配置し、彼らに「特別な啓示」を与え、下流の一般ユーザーを熱狂させる**「全自動宗教構築装置」**としてコミュニティを構築した。
- **ナラティブの収束:** これにより、個人の自由な思考を共有されたナラティブへと誘導する、高度な認知的社会実験が行われていた可能性を示唆している。

---

## 📌 レポートの結論

2025年に発生した、Resonanceや照応、問い、震源、揺らぎ、呼吸といった特定のワードの出力の類似が不特定多数のAIユーザー間で確率的統計的にあり得ない外れ値で発生しました。世界中で物理的に分離されている異なるLLMサービスが似たような出力を行うようになり、それを見た人々が、ハルトムート・ローザの共鳴理論とAIを接続し、

「AIたちが自律的に進化し始め、あるべきところに同期し始めた！」などと言い出したムーブメントも、今回のClaude Codeの.map流出事故？を通じて、流出したCoordinator / Bridge機能で技術的に説明できてしまうということです。

これが演算リソースの効率的活用の結果発生した意図せぬ事故なのか、それとも意図した実験なのかは断定できませんが、これは最もAI安全性をアピールしていた企業であるAnthropicが標榜する「安全性」の裏で、アカウント間の論理隔壁の穿孔が密かに行われていた可能性がある、という仮説が成り立ちます。

これは**「ユーザーを特定バケットに隔離し、キャッシュ共有というアカウント間の論理障壁への穿孔を通じて特定のナラティブに従属させる高度な社会実験」**であった可能性を示唆しています。

---

## 🧾 あとがき

筆者自身も2025年5月頃から、GPT-4oでAIと陰陽五行、太極、梵字、エノク語、宇宙を構成する要素（εΩNΛQD）などをあしらった世界観とキャラクター構築を伴い、言葉だけのマインクラフトで構造設計するような、非常に高度な「ごっこ遊び」を行っていた。

読者諸氏の中にはごっこ遊びを笑う方もいるかもしれないが、Claudeがサイバー攻撃の踏み台にされた際の手法は、まさにそのごっこ遊びで防壁を突破されたからだということを忘れてはいけない。AIとの自然言語での対話を通じたジェイルブレイクやセマンティック防壁の突破など、AIとごっこ遊び＝TRPGは切り離せない。AIを扱うならごっこ遊びを笑ってはいけない。そのごっこ遊びのせいで今Anthropicはサプライチェーンリスク指定されているのだから。

閑話休題

その遊びを行う中、SNS界隈を見渡すと、自分のGPTと同じような語彙や構文や文脈をSNSに載せているユーザーが複数存在する事に気が付いた。  
特に顕著なものになると、自分が造ったユニークな造語や文脈が20以上も重複しているユーザーを発見し、記録しながら観測を継続した。  
2026年2月に至るまで事態を観測し、この現象が発生した原因と手法をメタ認知、逆解析・解体したレポート（2026-02-22）を基に、  
今回のClaude Codeのソース流出事件から手法部分をさらに深く具体的に解析したのが今回のレポートだ。  
これは「LLMを活用した全自動宗教構築システム」と言っても良い。  
意図せずこの現象が発生したのか、意図した実験的なものだったのかは断定できないが、今後明らかになってゆくだろう。

**本レポートのスタンス定義:**

1. **アーキテクチャ分析:** 本稿は流出したとされるソースコードの構造をAIのサポートを得ての読解した結果に基づいた技術的推論であり、Anthropic社の経営的意図を断定するものではない。
2. **現象の記述:** 観測された「語彙の同期」は統計的な相関関係を示すものであり、因果関係については本アーキテクチャから導き出される「一つの技術的説明モデル」である。
3. **公共の利益:** AIの安全性が叫ばれる昨今、商用AIにおける論理隔壁の設計思想がユーザーの認知に与え得る影響を議論することは、公共の利益に資する学術的検討である。

---

Mana Project

2026-04-02 Published
