# Smart-Contract-Docs
CURL run contract
curl --location --request POST "http://localhost:8181" \
  --header "Content-Type: application/json" \
  --header "authorization: 633f9446af5028b89a730b6fafd11785371fd3dc948311b9ea1a3dfe61739cfb" \
  --header "hash: 4c5c3eb76c7a8368a5ad7bb52f9da0ef7be4552622d6b8e0f59e675af4e77f0d" \
  --data "{
	\"jsonrpc\":\"2.0\",
	\"method\":\"contract_run\",
	\"params\":[\"`your contract address`\", \"`your method`\", `your params`],
	\"id\":1
}"
