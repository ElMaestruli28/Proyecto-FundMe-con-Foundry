-include .env

build:; forge build
deploy-sepolia: forge script --rpc-url $SEPOLIA_RPC_URL --private-key $(PRIVATE_KEY) --broadcast --verify --etherscan-api-keys $(ETHERSCAN_API_KEY) -vvvv