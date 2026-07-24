# codex-practice

## CIデバッグ練習

`calculator.py` と標準ライブラリの `unittest` を使い、GitHub Actionsで
テストを実行します。最初のドラフトPRでは意図的にテストを失敗させ、
チェックログから原因を特定して修正する流れを練習します。

```bash
python -m unittest discover -s tests -v
```
CodexとGitHubの操作を練習するためのリポジトリ
