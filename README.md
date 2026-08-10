# kon-assets — @ik_aide 投稿画像の公開ホスティング

[@ik_aide](https://x.com/ik_aide) の X 投稿に添付する画像を配信するための公開リポジトリです。

- 画像は投稿と同時に公開されるものだけを置いています（非公開情報は含みません）
- 配信URLの形式: `https://raw.githubusercontent.com/ikytjobs-blip/kon-assets/main/<年>/<月>/<file>.png`
- 生成は [ai-org](https://github.com/ikytjobs-blip/ai-org) の PIL パイプライン（外部API不使用）

## なぜGitHubなのか
以前は Supabase Storage を使っていましたが、無料枠のプロジェクトが**無操作で自動休止**し、
画像URLが発行できない状態に気づかないまま「→詳しくは画像で」と書いた画像なし投稿を
配信し続ける事故が起きました（2026-07〜08）。
GitHub は休止が無く、追加の契約も課金も不要なため、同じ失敗モードを構造的に回避できます。
