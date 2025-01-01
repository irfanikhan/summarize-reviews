This is an AI generated summaries of customer reviews for an e-commerce storefront.

The demo takes a set of customer reviews, and uses an LLM to create summaries of those reviews.
It then displays the summary and the reviews in a demo UI.

The benefit of such an AI summary is that the user can get a quick overview of the sentiment
of reviewers of the product without reading them all.

## Getting Started

- Install the dependencies
- Run the development server:

```bash
pnpm dev
```

## AI key

This project requires an API key for Perplexity's inference API.

Any other LLM model can be connected via minimal changes to `lib/ai-summary.ts`.
