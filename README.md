## 『確率の半歩先 予測・拡散モデルに挑む前の30話』 サポートページ

### 書籍情報
大久保 潤 著,『確率の半歩先 予測・拡散モデルに挑む前の30話』 講談社 (2026）のサポートページです。

出版社のページ: https://www.kspub.co.jp/book/detail/5439357.html

<div align="center">
<img src="https://github.com/junohkubo/probability_half_book/blob/main/figs/jacket_RGB.jpg" width="200px">
</div>

（更新: 2026.7.9 誤植情報掲載）

***
### 第1刷、第2刷の誤植
（ミスがあり、大変申し訳ありません）
- (2026.7.9) クープマン作用素は、期待値をとりたい関数を「時間を逆向きに発展させる」ことで、手前の時刻の座標を入力して、時間発展後の条件付き期待値を与える関数へと変換します。そのため、クープマン作用素を考えるときには、時間の発展が「逆向き」になります。これにより、クープマン作用素を途中の時刻で区切り、二つのクープマン作用素に分解すると、順番を入れ替えて記載する必要がありますが、元の時間順序のままで書いてしまっていました（申し訳ありません）。これに伴い、以下の点に修正が必要です。
  - p.271の図28.3の青点線枠内の左上の式:
  「$`\mathcal{K}_{s+u,0} =  \mathcal{K}_{s+u,s} \mathcal{K}_{s,0}`$」&rarr;「$`\mathcal{K}_{s+u,0} =  \mathcal{K}_{s,0} \mathcal{K}_{s+u,s}`$」
  - p.271の図28.3の青点線枠内の右上の式:
  「$`\mathcal{K}_{s+u,s} \mathcal{K}_{s,0}`$」&rarr;「$`\mathcal{K}_{s,0} \mathcal{K}_{s+u,s}`$」
（緑色と青色の下線も合わせて入れ替え）
  - p.272の式(28.6):
  「$`\mathcal{K}_{s+u,0} =  \mathcal{K}_{s+u,s} \mathcal{K}_{s,0}`$」&rarr;「$`\mathcal{K}_{s+u,0} =  \mathcal{K}_{s,0} \mathcal{K}_{s+u,s}`$」  
  - p.273の式(28.9)の左辺（最初の式）:  
  「$`\mathcal{K}_{s+u,s} \mathcal{K}_{s,0} \varphi(x)`$」&rarr;「$`\mathcal{K}_{s,0} \mathcal{K}_{s+u,s} \varphi(x)`$」（数式の下のコメントもずらす）  
  - p.275の式(28.13)の最後の一つ手前の式の丸括弧内第1項目、および、p.276の式(28.16)の左辺:  
  「$`\mathcal{K}_{s+\Delta t,s} \mathcal{K}_{s,0} \varphi(x)`$」&rarr;「$`\mathcal{K}_{s,0} \mathcal{K}_{s+\Delta t,s} \varphi(x)`$」  

（このミスは、以下のURLでご指摘いただきました。どうもありがとうございます）  
https://x.com/edam0z9/status/2074980915345068345


***
### 補足資料：第5話での「時間順序積」について （2026.6.25掲載）

本書の第5話において、「時間順序積」という用語を紹介しています。ただし、紙面の都合と、本書の本題から少し外れるため、その詳細には触れていません。よく見かける道具ですので、本書の議論とのつながりについて、簡単な補足資料を作りました。

（以下のリンクで、githubページ内に設置した補足資料のPDFのページに移動します）


[supplemental-1.pdf](https://github.com/junohkubo/probability_half_book/blob/84a7601176906ebcf8ac7be695e167dfda48886e/assets/supplemental-1.pdf)
