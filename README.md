# Embedding Cost Calculator

Static calculator estimating text-embedding generation cost across every current OpenAI, AWS Bedrock, and Google Gemini embedding model, given a candidate/document count and average tokens per item.

Live: https://srinivas1591.github.io/embedding-cost-calculator/

Pricing is hardcoded in `index.html` (see the `MODELS` array) and was verified against official provider pricing/docs pages as of **2026-07-22**. None of these providers expose a live pricing API, so this data needs manual re-verification before relying on it for budget decisions — check:

- [OpenAI pricing](https://platform.openai.com/docs/pricing)
- [AWS Bedrock pricing](https://aws.amazon.com/bedrock/pricing/)
- [Gemini API pricing](https://ai.google.dev/gemini-api/docs/pricing)
- [Gemini deprecations](https://ai.google.dev/gemini-api/docs/deprecations)

No build step — it's a single self-contained `index.html`. To update pricing, edit the `MODELS` array and the "verified as of" date directly.
