# whatday_today_app

graduation work for RUNTEQ

■ サービス概要
どんなサービスなのかを３行で説明してください。

- ページをクリックしたその日について、日本の暦を教えてくれるサービスです。
- 季節、旬の食べ物などのトピックの中から暦に関する簡単なクイズを出し、小さなアクティビティを提案します。
- その日についてのメッセージを投稿する機能があり、ユーザー間で共有できます。

■ このサービスへの思い・作りたい理由
このサービスの題材となるものに関してのエピソードがあれば詳しく教えてください。
このサービスを思いつくにあたって元となる思いがあれば詳しく教えてください。

- 日本の伝統に興味があり、趣味で着物や小物を作ります。作った着物やその小物を身につけるとき、昔は、どのような時に、どのような気持ちで着用していたのだろう、と想像することがあります。
- 日本の暦は、今ではカレンダーに大安や仏滅などで見かける程度ですが、昔の人々が使っていた暦を知ることによって、季節の移ろいや暮らしの一部を共感したりインスピレーションを得ることができたらいいなと思いました。

■ ユーザー層について
決めたユーザー層についてどうしてその層を対象にしたのかそれぞれ理由を教えてください。

- 30 代〜40 代サラリーマン男女：
- 毎日忙しくて、伝統とか季節とかそんなことどうでもいいけど、電車に乗っていたりちょっとした空き時間にページを開けてくれて、昔の行事とかちょっとした慣習や認識を「そんなことがあるんだ」、「昔はそんなふうに考えていたんだ」、と新鮮に感じてくれるのではないか思いました。
- SNSの使用に慣れている年代ですので、ポスト・シェア機能でこのサービスの利用が広がるのではないかと思いました。


■ サービスの利用イメージ
ユーザーがこのサービスをどのように利用できて、それによってどんな価値を得られるかを簡単に説明してください。

- 簡単なクイズでその日のことを知るすることができます。
- 営業や会議で人に会った時、その日のちょっとした雑談、スモールトークに使ってもらうことができます。
- アクティビティを提案して、その日の過ごし方や予定の参考にしてもらうことができます。
- 毎日、新しいトピックや提案がありますので、その日一日の気持ちや行動に新鮮さやインスピレーションを少しでも感じることができればと思います。
- 日本人の昔の習慣や行事を知ることで、今日という一日について昔の人の行動様式に共感し、現代の人と共有することができます。

■ ユーザーの獲得について
想定したユーザー層に対してそれぞれどのようにサービスを届けるのか現状考えていることがあれば教えてください。

- 友人や知り合いに紹介します。
- X で公表します。今はそれほど X を利用していませんが、それまでに学習の経過を X でつぶやいておいて、その成果として発表します。
- オフラインのイベントに参加し、仲良くなれた人に紹介します。
- イベントで参加したコミュニティで伝えます。
- もしこのサービスが面白いと思ってもらえたら、SNS機能で使用が広がることを期待しています。

■ サービスの差別化ポイント・推しポイント
似たようなサービスが存在する場合、そのサービスとの明確な差別化ポイントとその差別化ポイントのどこが優れているのか教えてください。
独自性の強いサービスの場合、このサービスの推しとなるポイントを教えてください。

1. Google で、キーワード「日本の暦」で検索した場合、今の所、類似のサービスはヒットしませんでした。
2. SNS機能については、すでに著名なサービスがあるので、次の点を差別化ポイントと考えます。
    - その日の暦に関して、365 日異なるクイズを出ししますので、その日の暦について豆知識を獲得できます。
    - 季節、旬の食べ物、伝統行事、色、野草の中からランダムにトピックを選んで、その一日の中での小さなアクティビティを提案します。
    - POST 機能でその日の何か（行動したこと、思ったこと）についてメッセージを残すことができ、また、他のユーザーと共有できますが、そのメッセージは次にの日になるとトップページには表示されなくなります。
    - しかし、来年以降の同じ日付には、そのメッセージが表示され、去年（とその年以前）のメッセージを見ることができ振り返りの機会があります（ユーザー関連の機能で、そのユーザーのメッセージの一覧表示、編集・削除可能）（トップページには検索機能があり自分のメッセージのみ表示することが可能）。
    - この機能により、今日のメッセージを残しておこうというきっかけ、また明日もこのサービスを利用しようというきっかけとなり、来年以降には（このサービスが存在しているか不明ですがあるとすれば）ちょっとしたタイムカプセル的なメッセージになるかもしれないと思います。

■ 機能候補
現状作ろうと思っている機能、案段階の機能をしっかりと固まっていなくても構わないので MVP リリース時に作っていたいもの、本リリースまでに作っていたいものをそれぞれ分けて教えてください。

1. 今考えているサービス全体の概要
    - トップページは、次のように考えています。
    [![Image from Gyazo](https://i.gyazo.com/addb3c8ac5b509bbdfb5295305f182da.png)](https://gyazo.com/addb3c8ac5b509bbdfb5295305f182da)

2. MVP リリース時に作っていたいもの
   1. その日の暦の表示（メインの単語）
      - 書籍やネットの情報から引用して自身で用意します。
      - メインの単語の表示に必要なDB（365日分）
   2. その日の関する暦のクイズ＆正解
      - メインの単語をキーワードとして、AIを介して生成します。
      - 表現などは、自身で監修します。
      - クイズ＆正解の表示に必要なDB（365日分）
   3. アクティビティの提案
      - 例：旬の食べ物から今日のレシピ、伝統行事から観光スポット、色から小物・インテリア、季節から野草について、アクティビティ（たいした事ではない）を提案します。
      - 書籍やネットの情報を参照し、自身で用意します。
      - AIによる生成を補助的に使用します。
      - アクティビティの提案内容のDB（１ジャンル、365日分）
   4. もっと知りたい場合の検索ワードの提案
      - 書籍やネットの情報から引用して自身で用意します。
      - 検索するためのワード表示のためのDB（365日分）
   5. ユーザー登録・基本的なログイン機能
   6. ポスト機能（本文、写真（サムネール作成））
      - その日と同じ日付のポストのみを表示します。
      - ポストは、ニックネームで検索できるようにします。
   7. マイページ・ポスト編集機能
   8. 日本の暦についての解説ページ
      - 書籍やネットの情報を参考にして自身で用意します。
   9. Google、参考ページへのリンク

[![Image from Gyazo](https://i.gyazo.com/8a2de66f2a8369ee75b16b28870643fb.png)](https://gyazo.com/8a2de66f2a8369ee75b16b28870643fb)

2. 本リリースまでに作っていたいもの
   1. アクティビティの提案には、2つのジャンルからランダムに選択して表示できるようにします。
      - アクティビティの提案内容のDB（１ジャンル追加（合計2ジャンル）、365日分）
   2. ログイン機能（Remember me）

3. 以降のアップデート要素
   1. アクティビティの提案には、トピックを選択できるようにする（例：どんな提案をチョイスしますか？）
      - 食、食事、旬の食べ物、レシピ
      - 伝統行事、外出スポット
      - 季節、ハイキング、野草、観光スポット
      - 色（持ち物、インテリア等）、ショッピング
   3. カレンダー表示、知りたい日付をクリックする（解説やアクティビティ提案を表示）
   4. 記念日の追加機能：ユーザー専用の特定の日の登録機能
      - 日付、タイトル、内容
   5. リマインド機能
      - 何日前に通知を送るか \*提案が必要かどうか（トピックから選ぶ）
   6. 検索機能：日付、キーワードで日付を逆引き（このアプリの DB から）
   7. AI の Chat 機能：もっと暦について知りたい場合知りたいワードについて調べることができる


■ 機能の実装方針予定
一般的な CRUD 以外の実装予定の機能についてそれぞれどのようなイメージ(使用する API や)で実装する予定なのか現状考えているもので良いので教えて下さい。

- クイズ（３択、正解、解説）：Ruby/Rails、または JavaScript、Hotwire
- ログイン機能：Remenber me
- ポスト機能（本文、写真）：ImageMagick
- 検索機能（日付、キーワード）：Stimulus Autocomplete（Rails7 ）
- リマインド機能：ネットで調べる
- AI の Chat 機能：ChatGPT を調べる
