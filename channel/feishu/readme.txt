

# 注意使用以下命令测试时，请确认应用没有配置 Encrypt Key。如果应用配置了 Encrypt Key，那么 HTTP 的请求包体会有加密。

curl -v --location 'https://briefly-active-arachnid.ngrok-free.ap' \
--header 'Content-Type: application/json' \
--data '{
  "challenge": "<test code>",
  "type": "url_verification",
  "token": "<your verification token>"
}'
