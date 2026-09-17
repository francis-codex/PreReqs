# PreReqs

Solana Turbin3 TypeScript prerequisites, kept in `airdrop/`.

- `keygen.ts`: create a keypair
- `airdrop.ts`: request devnet SOL
- `transfer.ts`: send SOL and empty a wallet after fees
- `enroll.ts`: register on the Turbin3 prerequisite program with Anchor

```bash
cd airdrop
yarn install
npx ts-node keygen.ts
```

Devnet only. Keep keypair files out of git.
