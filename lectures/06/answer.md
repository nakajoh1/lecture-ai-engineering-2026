# 第6回 解答

## 演習

<!-- [tool call] の行は、表示された行をそのまま貼り付けてください。終わらなかった STEP は、空欄のままでかまいません。 -->

- STEP 1 のツールの名前：
- STEP 2 の [tool call]：
- STEP 3 の [tool call]：
- STEP 4 の [tool call]：
- 気づき・疑問：

## 宿題

<!-- 基礎・実装・発展のどれか1つに取り組めば完了です。 -->

- 取り組んだレベル：基礎 
- やったこと：app/mcp_server.py で server.tool()(tools.get_lecture_summary) を追加して保存し，uv run python -m app.mcp_agent --trace "第3回の要点を教えて" を実行してトレースを確認した．
- 結果：glossary_get_lecture_summary({'lecture': 3}) が呼び出され，第3回（AIエージェント）の要点と「関係する回：第3回」が出力された．
- 気づき・疑問：保存直後もエクスプローラーに M マークが残っていたが，未保存の印ではなく Git 上で変更済み（Modified）を示す表示だった．また，モデルが混み合っているときは 503 エラーになる場合があることがわかった．
