#test commit
#test Alertmanager
curl -w '\n' -i --user 'admin:admin'   --header 'Content-Type: application/json'   --data '[{"labels":{"alertname":"test_Soloviev-Alex_Netology", "team":"Danger"},"endsAt":"2024-04-21T00:10:53-03
:00"}]'   http://127.0.0.1:9093/api/v1/alerts
