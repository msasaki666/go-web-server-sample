# go-web-server-sample

cloud runのコールドスタートが、GolangのWebサーバーではどの程度か体感するためのechoサーバー

## deploy

gcloud run deploy go-web-server-sample --source . --max-instances 1 --port 1323 --region asia-northeast1 --allow-unauthenticated
