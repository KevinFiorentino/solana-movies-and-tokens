# Solana Multi Account Program

#### Usage

1. Deploy program
2. Initialize token mint (see client-token)
3. Create movies review (see client-movie-review)
4. Receive tokens for every movie review or comment

### Deploy Program

- `solana config set -u l`
- `solana-test-validator` (on another terminal)
- `cargo build-sbf`
- `solana program deploy target/deploy/solana_movies_and_tokens.so`

### Test Program

- `cargo test-bpf`
