# 応募効果シミュレーター（画面）

トルトルくんの営業が使う、応募効果シミュレーションの画面（静的 HTML 1枚）。
求人原稿の URL／tldv の URL／原稿の本文を貼ると、先方へ送る2行の文面が出る。

- 画面：GitHub Pages（この index.html）
- 計算・読み取り：Google Apps Script の API（index.html の `API`）。API キーは Apps Script 側のスクリプト プロパティにあり、ここには無い
- 画面→API は Cookie を送らない（`credentials: 'omit'`）ので、Google アカウントの状態に関係なく動く
