in order to set up metaplex, choose a folder and run the following commands.

git clone -b https://github.com/metaplex-foundation/metaplex.git

cd metaplex/js

yarn install

You can check that everything is working by running the Candy Machine CLI command:

ts-node packages/cli/src/candy-machine-v2-cli.ts --version

