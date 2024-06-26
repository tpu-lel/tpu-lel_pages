---
title: "研究内容"
---

# 研究内容

<h2>人の<u>認知心理</u>に関わる理論の設計と<u>人工知能</u>の融合による<br/>「知的な」学習支援システムの開発</h2>

近年、人工知能技術の発展が目覚ましいですね。

コンピュータがより人間の役に立つためには、ユーザである「人間」が「どのように物事を考えるか（認知するか）」を考えることが大切です。

本研究室では「人の認知の心理学」を研究し、それを知的に理解し、学習を支援するシステムを開発しております。

「心理学ベースで人の心理を理解し、うまくやる気を引き出してくれるコンピュータ」

「人と同じように問題を理解し、解くことができる知能を有するコンピュータ」

面白いと思いませんか？

<div style="display: flex; justify-content: space-around; align-items: start;">
    <div style="text-align: center; margin: 10px;">
        <img src="/images/research/intro1.png" style="width: 100%;">
        <!-- <p>キャプション1</p> -->
    </div>
    <div style="text-align: center; margin: 10px;">
        <img src="/images/research/intro2.png" style="width: 100%;">
        <!-- <p>キャプション2</p> -->
    </div>
    <div style="text-align: center; margin: 10px;">
        <img src="/images/research/intro3.png" style="width: 100%;">
        <!-- <p>キャプション3</p> -->
    </div>
</div>

## 東本の研究コンセプト

私は元々ゲームなど遊びが大好きでした。遊びは楽しい。楽しいということは強いモチベーションを生み出します。なぜ、今「学習」というテーマについて研究しているのか。「教育」は先生主体ですが、**「学習」は学び手（学習者）主体**です。ゲームも学習も「何かを達成できて、楽しい」という共通性を持っています。ただ、学校教育では「教師による一方的な押し付け」が学習をつまらないものにします。

本研究室では、「教師による一方的な」教育ではなく、「学習者主体」の楽しい学習を支援するシステムを設計します。「何が楽しいか」、「何を学ぶべきか」、「なぜ学ぶべきか」？ これらは、学習者がどのように考えているか、そして学習者が自分のことをどれだけ理解しているかに関係します。そのため、人の認知に関する心理（認知心理学）に基づいて、研究を進める必要があります。また、「教師による一方的な」教育を回避し、「学習者主体」になるには、「**学習者がまずは行動し、それに教える側が対応する**」ことが必要です。しかし、教師一人ですべての学習者の行動に対応することも大切です。本研究室では、**認知心理学に基づく人工知能技術により学習者の活動を診断し、フィードバックを与えるシステム**を設計・開発します。

## 心構え
利用者の役に立ち、利用者が楽しんでくれる研究を行います。

研究している本人が「意味がある」「役に立つ」と思えるものを作ってもらいます。


## 研究事例

### （1）誤りの可視化を元にした学習支援システム

間違ったときに「それ間違ってるよ」と指摘されるとやる気がなくなりますよね。これを否定的フィードバックと言います。人は否定されるとやる気がなくなります。

そこで、「それが正しいとするとどうなるか考えてみよう」と促すとやる気が出ます。これを肯定的フィードバックと言います。

誤りの可視化では「学習者の解答が【もし正しいとしたら】どんなおかしなことが起きるか」をコンピュータが「可視化」して表現します。

**「人のやる気を引き出すための認知」「人の概念の変容のための認知」と「コンピュータによる仮想世界のシミュレーション」を融合した研究です。**

<div style="display: flex; justify-content: space-around; align-items: start;">
    <div style="text-align: center; margin: 10px;">
        <img src="/images/research/ebs1.png" style="width: 70%;">
        <p>力学の例です。上の問題では本当は垂直抗力が働いているのですが、重力しか働いていないと思って学習者が解答すると...</p>
    </div>
    <div style="text-align: center; margin: 10px;">
        <img src="/images/research/ebs2.png" style="width: 57%;">
        <p>「あなたの解答に従うと、物体が地面に沈み込んでしまうことになる」という様子をコンピュータが可視化し、「自ら誤りに気付く」ことを促します。</p>
    </div>
</div>

### （2）教える活動を体験させるためのエージェントTAME（Teachable Agent Module for Error-visualization）

学習活動の中で最も効果的なことは「人にモノを教えること」です。

しかし、日常ではちょうど自分が教えるのに適した相手がいることは少ないです。そこで、コンピュータが教えられるエージェントになります。

**「人に教えることによる学び」と「人の振舞いのシミュレーション」を融合した研究です。**

<div style="display: flex; justify-content: space-around; align-items: start;">
    <div style="text-align: center; margin: 10px;">
        <img src="/images/research/tame1.png" style="width: 50%;">
        <p>教えられるエージェントが解いた問題に対して、ユーザは「この解き方がおかしい」などを指摘します。</p>
		<p>エージェントは、学習者の行動によって理解を深めます。</p>
    </div>
</div>

### （3）プログラミングにおける「部品知識の獲得」を支援するための学習支援システム

プログラミングの授業では、if文やfor文などの使い方を覚えてプログラムを作ることが多いです。

しかし、人の問題解決のプロセスでは、「チャンキング」というまとまりとして情報をとらえて一括処理することが一般的で、if文やfor文などのレベルではなく、一定のまとまりのある部品を獲得することがプログラミングスキルの向上に不可欠です。

本研究ではプログラミングにおいて「部品知識」の獲得を支援する研究を行っています。

**「人のスキーマ（部品としての理解）としての認知」と「人の状態に適応したフィードバック技術」を融合した研究です。**

<div style="display: flex; justify-content: space-around; align-items: start;">
    <div style="text-align: center; margin: 10px;">
        <img src="/images/research/brocs1.png" style="width: 90%;">
        <p>c=a,a=b,b=cという3行のコードは「Swap」という機能を有する部品知識として獲得します。</p>
		<p>さらに、その部品を拡張していくことで、次第に大きなプログラムも作ることができるようになります。</p>
    </div>
    <div style="text-align: center; margin: 10px;">
        <img src="/images/research/brocs2.png" style="width: 50%;">
        <p>システム画面です。部品を組み合わせて目標となる部品を作ります。目標部品を作り終えると、次はその目標部品を使って、新しく拡張した目標部品を作る課題に移ります。</p>
    </div>
</div>

### （4）「他の人のコードの良いところを取り入れる」ためのゲームベースのロボットプログラミング型知識共有プラットフォーム

自分以外の人のプログラムのコードを見ることは良い学習につながるはずです。しかし、実際はそのような機会は少なく、また、他の人のコードがどのように優れているかを理解することも難しいです。

そこで、本研究では自分や他の人のコードを評価し、ランキング形式で表示し、良いところを可視化します。同時にゲーム形式で楽しいです。

**「ゲーミフィケーションによる学びの認知」「協調学習」と「ロボットプログラミング技術」「知識共有技術」を融合した研究です。**

<div style="display: flex; justify-content: space-around; align-items: start;">
    <div style="text-align: center; margin: 10px;">
        <img src="/images/research/robot1.png" style="width: 50%;">
        <p>ロボットに動作をプログラミングし、作物をできるだけ収穫できるようにします。</p>
    </div>
    <div style="text-align: center; margin: 10px;">
        <img src="/images/research/robot2.png" style="width: 60%;">
        <p>収穫数と使用コストに応じてランキングが表示され、他の人のコードの良い点を学べます。</p>
    </div>
</div>

### （5）「プログラミングにおける動き方（振る舞い）を理解するため」のトレース演習システム

プログラムについての理解を深めるためには、各行で何が行われているかを理解することが大切です。

そこで、本研究では「どのような順番で行が実行されるか」と「各行で何が行われているか」を学習者に与えるトレース演習課題を提案しました。

さらに、「もし正しいときはどのような結果になるか」も可視化し、学習者自身に誤りに気付かせます。

**「対応付けた構造的な知識獲得」「操作を伴った認知」と「コンピュータの振舞い自動制御機能」を融合した研究です。**


<div style="display: flex; justify-content: space-around; align-items: start;">
    <div style="text-align: center; margin: 10px;">
        <img src="/images/research/trace1.png" style="width: 100%;">
        <!-- <p>キャプション1</p> -->
    </div>
    <div style="text-align: center; margin: 10px;">
        <img src="/images/research/trace2.png" style="width: 100%;">
        <!-- <p>キャプション2</p> -->
    </div>
    <div style="text-align: center; margin: 10px;">
        <img src="/images/research/trace3.png" style="width: 100%;">
        <!-- <p>キャプション3</p> -->
    </div>
</div>
