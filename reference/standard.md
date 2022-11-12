# 記事の標準の書式について

# 項目
扱う内容  
タイトル  
プログラムの解説  
数学的な解説  
プログラム例 (言語ごとに)  

# 項目ごと

## 扱う内容
扱う内容が分かりやすく、特段の前提知識が要らない場合は不要  
  
前提知識の解説、その記事へのリンク ※リンクは未実装なので実装され次第  
扱う内容が曖昧な場合は扱う内容の説明  

## プログラムの解説
プログラム言語で実装している内容を自然言語(日本語)で書く  
常体(普通体)を基本に淡々と書く  
  
 例)  
yを0にする。 ← y = 0;  
yに1を足す。 ← y += 1; or y++;  
ループを用いて0からyまでiを1づつ増やす。 ← for (i = 0;i < y;i++) {}  
ループでyから1を引く。 ← for () { y--;}  
0を返して終了。  
  
本文中の変数,定数　斜体 ※未実装なので実装され次第  
コード　コードブロック  

## 数学的な解説
本文中の変数　斜体 ※未実装なので実装され次第  
敬体(丁寧体)を基本に淡々と書く  
演算の場合は、例があると良い  

 例)
2x = 10 + y になるので、
y = x - 5 になります。  
例) x=10 なら、 y = 10-5 = 5

## プログラム例
できれば、javascript, c, c#  
その他の言語は自由に  
  
型指定が必要な言語は、  
符号なし整数 int, 符号付き整数 uint, 浮動小数点 double  
を基本にする  
  
できるだけ動作確認をする  