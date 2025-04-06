# sealware
git clone https://github.com/MystenLabs/seal.git
cd seal/examples
cd move/allowlist
sui move build
sui client publish --gas-budget 100000000
cd ../../frontend/allowlist
npm install
npm run dev

cd move/subscription
cd ../../frontend/subscription
npm install
npm run dev
