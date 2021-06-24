# Awesome Solana Cheatsheet
🌟 A Solana Cheatsheet for Easy Copy & Paste for Busy Devs. 👻 

## Solana CLI
1. `solana --version`: Get the version of Solana CLI.
2. `solana cluster-version`: Get the version of the Solana cluster that you are currently set to.
3. `solana config get`: Get current RPC URL of the connected Solana cluster and show key pair path to your local wallet. 
4. `solana config set --url https://api.devnet.solana.com`: Set the Solana cluster to devnet.
5. `solana airdrop 10`: Get 10 SOL for free to your default wallet locally! (Of course not available on mainet XD)
6. `solana balance`: Check your current SOL balance in the default wallet.
7. `echo 'export RUST_LOG=solana_runtime::system_instruction_processor=trace,solana_runtime::message_processor=info,solana_bpf_loader=debug,solana_rbpf=debug' >> ~/.bashrc`: Enable Rust logs for debugging.
8. `solana-test-validator --log`: Start a single node Solana cluster with logs. Note that a folder named `test-ledger` will be created to store the local cluster data in the directory you run this command. Leave this node running in a spare terminal. See more in the [docs](https://docs.solana.com/developing/test-validator).
9. `solana config set --url http://127.0.0.1:8899`: Set Solana CLI to interact with local cluster on port 8899. 
10. `solana logs -u localhost`: Show the explicit logs when you interact with the Solana smart contracts.
11. `solana program deploy <your_program_path>`: Deploy smart contracts on the current Solana cluster.

## Anchor
1. `cargo install --git https://github.com/project-serum/anchor anchor-cli --locked`: Update the anchor CLI to the lastest version.
2. 

## Awesome References
1. [Building SmartContracts With #Solana and #Rust by David Choi](https://youtu.be/gA7hFdq2h9Q)
2. 