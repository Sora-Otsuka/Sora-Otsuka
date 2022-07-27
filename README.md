### プロフィール
- **兵庫県立大学社会情報科学部**
  - 機械学習や統計学、データハンドリングなどを含めたデータサイエンスを学習しています。

- **研究室: 湯本研究室**
  - テキストデータやWEBデータに対するデータマイニングを専門とする研究室
  
- **研究内容: 自然言語処理・画像処理の2領域の深層学習モデルを用いたスライド形式PDFからの文書要約**
  - **研究の動機・意義**
    - スライド形式PDFからの情報抽出を行うことによる、文書からの議事録の作成や、文書からのインデックスの作成による効率的な文書検索を目的としている。
    - 世の中には会社の提案資料や大学の授業資料、オープンソースなどにスライド形式のPDFがよく用いられている。
    - しかし現在の主要な文書要約タスクでは、構造的なプレーンテキストに対する要約が多くを占めており、PDFからの要約モデルはあまり考案されていない。
    - そこでPDFからの情報抽出を行うことができれば、効率的な文書検索や議事録の作成を行うことができる。そのため、現在の研究を行なっている。
    
  - **用いている手法**
    - PDFに埋め込まれているテキスト情報の抽出
    - 画像処理深層学習モデルであるEfficientNetを用いた画像分類
    - 自然言語処理深層学習モデルであるSentence-BERTを用いた文章のベクトル化
    - 画像処理と自然言語処理を組み合わせるために考案したオリジナルアルゴリズム
    
  - **新規性**
      - 自然言語処理と画像処理の両方の分野を組み合わせて、要約を行なっている。
      - 後述する「人間的要約」を可能にするために2つの全く異なる分野を掛け合わせている。
      - また、これらを掛け合わせるためにオリジナルのアルゴリズムを考案・使用している。
    
    - 画像要約の際に「人間的」という概念を用いている。
      - 人間はスライドを見る際に、言語的重要性と画像的重要性の両方から、そのスライドを判別している。
      - この研究ではスライドの見た目から得られる画像的重要性と、スライドに含まれる文章の言語的重要性の両方を、それぞれの分野の深層学習によって抽出している。
      - それによって、「人間がみているように」画像からの要約を行うことができる。
      
    

### 主な実績

- **ITベンチャー企業にて機械学習の実装業務**
  - 長期インターン兼アルバイトとして、現在まで機械学習の実装業務に従事している。
  - 主に自然言語処理を用いたテキスト分類や、データのハンドリング・可視化とその解釈を行うデータサイエンス業務を行なっている。
  - 自然言語処理では、古典的なモデルから深層学習モデルまで幅広いモデルを扱っている。
  - [実装で利用した一部の機械学習モデルに関する記事](https://qiita.com/sora-otsuka/items/83ea976236a82f6c6645)

- **社会人向け統計学セミナーの主催・資料作成・進行**
  - 上記ベンチャー企業と共同で、社会人向け統計学セミナーの主催・資料作成・進行を行なっていた。(2021/05/15~2022/04/16)
  - 毎回のアンケートを元に勉強会を常に進化させ、累計870名以上の方にご参加いただいた。
  - またその経験を活かして、上記勉強会を企業・個人向け研修事業に発展させた。また、講座の前段階として講座説明会を行なった。
  - [Pythonで学ぶ統計学入門](https://math-coding.connpass.com/event/208344/)
  - [プログラミングと統計学でDXの波にのる。講座説明会](https://anchorkobe.com/information/detail.php?id=10530)

- **個人事務所 AITech Co-Labo 開業**
  - 主にデータ分析・機械学習の実装業務、プログラミング・機械学習の教育事業に従事。
  - 教育事業の一環として、下記業界最大手プログラミングスクールにおける教材作成業務を行なった。

- **業界最大手プログラミングスクールにおける、Pythonコース・AIコース・データサイエンスコースの教材作成業務**
  - 上記の実績から、プログラミングスクールの教材を作成。
  - 作成した教材が運用開始されると、担当コースの人気度を全コース中2番目に上げた。

- **上記プログラミングスクールのコースディレクター就任**

  - 教材を作成し、それによってコース満足度を上昇させた経験から、上記プログラミングスクールのコースディレクターに就任した。
  - ディレクター就任後は、受講生からの意見と講師の意見の両方を聞き、より受講生にとって学習しやすい環境づくりを行った。
  
<!--
**Sora-Otsuka/Sora-Otsuka** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
