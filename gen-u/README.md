# GenU を触ってみましょう

* **今回の GenU 環境はトレーニング内で使用する時間帯だけで利用できます。**

## 環境へのアクセス

* 講師が URL とユーザー ID やパスワードをご案内します。

* ログイン後、下図が表示されたら、[スキップ] を選択して下さい。

## テキストを生成してみましょう

1. 左のメニューから **文章生成** をクリックします。

1. リストで、Claude Sonnet 4 を **Nova Lite** に変更します。

1. 「入力して下さい」の入力エリアに下記を入力します。

    - `生成 AI についてブログ記事を書いてください。`

1. 「文章の形式を指示して下さい。」の入力エリアに下記を入力します。

    - `マークダウン形式で出力してください。`

1. **実行** をクリックします。

1. 生成 AI に関するブログ記事が出力されることを確認します。

## 画像を生成してみましょう

1. 左のメニューから **画像生成** をクリックします。

1. リストで、Claude Sonnet 4 を **Nova Lite** に変更します。

1. 「どのような画像を生成したいですか？」の入力エリアに下記を入力します。

    - `公園で猫がくつろいでいる風景の画像`

1. 「シード」を **3** にします。

1. 「画像サンプル数」を **1** にします。

1. **公園で猫がくつろいでいる風景の画像** と入力した右横にある実行アイコンをクリックします。

1. 画像が 1 枚出力されることを確認します。

1. **おすすめスタイル**　で表示される **photographic** や **enhance** などをクリックして画像の内容が変更されることを確認します。

## 要約してみましょう

1. 左のメニューから **要約** をクリックします。

1. リストで、Claude Sonnet 4 を **Nova Lite** に変更します。

1. 「入力してください」の入力エリアに下記を入力します。

    - ```
      AWSは顧客からのすべてのフィードバックを受け、今日、私たちは AI 21ラボ、アンソロピック、スタビリティAI、そしてアマゾンのFMにAPIを介してアクセスできる新しいサービス「Amazon Bedrock」の発表を喜んで行います。
      Bedrockは、顧客がFMを使用して生成AIベースのアプリケーションを構築およびスケーリングする最も簡単な方法であり、すべてのビルダーにアクセスを民主化します。
      Bedrockは、スケーラブル、信頼性、セキュリティが高いAWS管理サービスを通じて、テキストと画像の強力なFM(アマゾンの新しい2つのLLMを含むTitan FMを含む)にアクセスする機能を提供します。
      Bedrockのサーバーレス体験により、顧客は自分が行おうとしていることに適したモデルを簡単に見つけ、すぐに開始し、独自のデータでFMをプライベートにカスタマイズし、インフラストラクチャを管理する必要なく(Amazon SageMakerのMLの機能であるExperimentsを使って異なるモデルをテストしたり、Pipelinesを使ってFMを大規模に管理したりするインテグレーションを含む)、慣れ親しんだAWSのツールと機能を使ってそれらを簡単にアプリケーションに統合およびデプロイできます。
      ```

1. **実行** をクリックします。

1. 要約された文章が出力されることを確認します。


## 翻訳してみましょう

1. 左のメニューから **画像生成** をクリックします。

1. リストで、Claude Sonnet 4 を **Nova Lite** に変更します。

1. 「入力してください」の入力エリアに下記を入力します。

    - ```
        AWS took all of that feedback from customers, and today we are excited to announce Amazon Bedrock, 
        a new service that makes FMs from AI21 Labs, Anthropic, Stability AI, and Amazon accessible via an API. 
        Bedrock is the easiest way for customers to build and scale generative AI-based applications using FMs, 
        democratizing access for all builders. Bedrock will offer the ability to access a range of powerful FMs 
        for text and images—including Amazons Titan FMs, which consist of two new LLMs we’re also announcing 
        today—through a scalable, reliable, and secure AWS managed service. With Bedrock’s serverless experience, 
        customers can easily find the right model for what they’re trying to get done, get started quickly, privately 
        customize FMs with their own data, and easily integrate and deploy them into their applications using the AWS 
        tools and capabilities they are familiar with, without having to manage any infrastructure (including integrations 
        with Amazon SageMaker ML features like Experiments to test different models and Pipelines to manage their FMs at scale).
    ```

## チャットで質問してみましょう

1. 左のメニューから **チャット** をクリックします。

1. リストで、Claude Sonnet 4 を **Nova Lite** に変更します。

1. チャットで下記の例の質問をしてみましょう。

    - 正しい回答が得られているかも確認してみましょう。
    - 同じ質問を何度か繰り返してきいてみましょう。

* 例1: `ショッピングサイトで有名なAmazon社を創設したのは誰でしょう？`

* 例2: `次の要件を満たす JavaScriptを含むHTMLを生成して下さい。ページの背景色は青です。ボタンをクリックすると、大きな見出しでフォントの色が白のHelloと表示されます。`

* 例3: `（ご自身の会社や組織）では社員が結婚するときに何日間休暇をもらえますか？`

* 例4: `東京の明日の天気はどうなるでしょうか？`

