curl --data '{"jsonrpc":"2.0","method":"parity_newAccountFromPhrase","params":["node0", "node0"],"id":0}' -H "Content-Type: application/json" -X POST localhost:8540

curl --data '{"jsonrpc":"2.0","method":"parity_newAccountFromPhrase","params":["node1", "node1"],"id":0}' -H "Content-Type: application/json" -X POST localhost:8541


curl --data '{"jsonrpc":"2.0","method":"parity_newAccountFromPhrase","params":["user", "user"],"id":0}' -H "Content-Type: application/json" -X POST localhost:8540

curl --data '{"jsonrpc":"2.0","method":"parity_newAccountFromPhrase","params":["user3", "user3"],"id":0}' -H "Content-Type: application/json" -X POST localhost:8540

curl --data '{"jsonrpc":"2.0","method":"parity_newAccountFromPhrase","params":["user2", "user2"],"id":0}' -H "Content-Type: application/json" -X POST localhost:8541

curl --data '{"jsonrpc":"2.0","method":"parity_newAccountFromPhrase","params":["user4", "user4"],"id":0}' -H "Content-Type: application/json" -X POST localhost:8541
