# ecom-profit-analyst

An agent that takes a small online store's messy exports and answers one question: where am I losing money, and what should I change?

Built for the "Build an agent that works" hackathon track. Uses neatlogs (run traces), Entire (code checkpoints) and cfo.ai (business plan).

## What it does

1. Reads the seller's files (orders, refunds, ad spend, product costs)
2. Finds data problems and fixes them, and says what it did
3. Works out real profit per product after refunds, shipping and ads
4. Digs into the worst products to find out why they lose money
5. Writes a report where every number is re-checked against the raw rows

## Status

Work in progress. Progress is tracked in the issues, one per stage.

## Honest notes

- Demo data is a public dataset with extra mess added on purpose (duplicates, mixed currencies, missing costs). The mess is generated with a fixed seed so we know the right answers.
- "Verified" means code recomputed the number from the data. It does not mean the model said so.

## License

MIT
