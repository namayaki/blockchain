# 発掘
curl localhost:5000/mine

# 全チェーン取得
curl localhost:5000/chain

# 取引追加
curl -X POST http://localhost:5000/transactions/new -H "Content-Type: application/json" -d '{
 "sender":"d4ee26eee15148ee92c6cd394edd974e",
 "recipient":"someone-other-address",
 "amount":5
}'
