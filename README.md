トリガー作成コマンド
```
curl -L \
  -X POST \
  -H "Accept: application/vnd.github+json" \
  -H "Authorization: Bearer ＜アクセストークン＞" \
  -H "X-GitHub-Api-Version: 2022-11-28" \
  https://api.github.com/repos/ueki-fcx/trial-dispatch-api/dispatches \
  -d '{"event_type":"aarun-dbt-workflow","client_payload":{"essage":"hello"}}'
```
