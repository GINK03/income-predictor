# 年収に効く要素とは何か  

## Getting Started
年収を表現するには様々なものから予想する必要があります。  

新卒での就職や、中途での就職にはどのような方法で選ぶのでしょうか。　　　

働き方などもあると思いますが、一つ重要な要素として年収（給与）の大きさがあるかと思います。  

[DoDaさま](https://doda.jp/)という転職サイトには大量の求人が記されており、この説明文から給与を予想することで、どのようなことが年収に影響をおよぼすのか、定量的に確認していきたいと思います  

## アルゴリズム
ElasticNetを利用します。単語ごとに重みをつけるBag of Wordsを利用しようと思います  

精度自体はさほどではないですが、解釈性がよいので、見通しが立てやすく、LassoとRidgeの双方の正則化項を利用します(ゴミみたいな情報が多いので正則化項は重要です)  

