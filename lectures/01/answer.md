# 第1回 解答

## 演習

- 講座に固有の質問（宿題の3レベル）へのモデルの回答（要約でよい）：
- 用語集の正しい意味と比べて気づいたこと：
- 表示できたトークン数（入力 / 出力）：

## 宿題

- 取り組んだレベル：基礎 / 実装 / 発展
基礎

- やったこと：
「LoRA とは何ですか？」を
[model] gemini-3.1-flash-lite
[model] gemini-3.5-flash-lite
[model] gemini-3.5-flash
[model] gemini-3.8-flash
で調べる。

- 結果：
[model] gemini-3.1-flash-lite
　⇒　[tokens] 出力: 754
[model] gemini-3.5-flash-lite
　⇒　[tokens] 出力: 537(一回目)、665(二回目)
[model] gemini-3.5-flash
　⇒　[tokens] 出力: 639(一回目)、709(二回目)
[model] gemini-3.8-flash
　⇒　[tokens] 出力: 800(一回目)、　

- 気づき・疑問：
　・文字数指定なしの指示の結果として、
　　概ねあとのリリースほど出力されるトークン数が多い
　　（但し、emini-3.1-flash-liteの結果はこの限りではない）
　・一回目よりも二回目のほうが出力されるトークン数が若干多い
　・最新のGemini3.8は応答が遅い。

