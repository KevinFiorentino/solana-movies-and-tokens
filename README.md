# Solana Multi Account Program

### Deploy Program Localnet

- `solana config set -u l`
- `solana-test-validator` (on another terminal)
- `cargo build-sbf`
- `solana program deploy target/deploy/multi_account_program.so`

### Usage Client

- Update the program address in `utils/constants.ts`
- Check the endpoint in `WalletContextProvider.tsx` as `http://127.0.0.1:8899`
- Change Phantom network to `localhost`
- Get localhost SOL with `solana airdrop 2 PHANTOM_WALLET_ADDRESS`
