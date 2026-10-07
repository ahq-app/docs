# docs

[AHQ](https://github.com/ahq-app/ahq) のドキュメントと JSON Schema を公開するためのリポジトリです。GitHub Pages で `https://ahq-app.github.io/docs/` として公開されます。

## JSON Schema

| ファイル | URL |
| --- | --- |
| `advanced-settings.json`（上級者向けオプション） | `https://ahq-app.github.io/docs/schemas/advanced-settings/v1.json` |

エディタで補完や値のチェックを使うには、`advanced-settings.json` の先頭に `$schema` を書きます。

```json
{
  "$schema": "https://ahq-app.github.io/docs/schemas/advanced-settings/v1.json"
}
```

`schemas/` の中身は、AHQ 本体のリポジトリを元に反映されるため、このリポジトリで直接編集しないでください。
