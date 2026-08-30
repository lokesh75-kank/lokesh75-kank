**Contributions:**

- [LangChain](https://github.com/langchain-ai/langchain)
- [OpenHands](https://github.com/OpenHands/OpenHands)
- [DeepEval](https://github.com/confident-ai/deepeval)
- [LiteLLM](https://github.com/BerriAI/litellm)

# 🌱 Open-work

- **[OpenHands](https://github.com/OpenHands/OpenHands)** (83K★, open-source AI software engineer) — fixed automation cards silently dropping required integrations that can't be installed as MCP servers, with i18n and regression tests · [Issue #16292](https://github.com/OpenHands/OpenHands/issues/16292) → [PR #16324](https://github.com/OpenHands/OpenHands/pull/16324) *(merged)*
- **[DeepEval](https://github.com/confident-ai/deepeval)** (17K★, LLM evaluation framework) — found and fixed nonexistent Claude model IDs that made every default-configured Anthropic evaluation fail with a 404 · [Issue #2993](https://github.com/confident-ai/deepeval/issues/2993) → [PR #2994](https://github.com/confident-ai/deepeval/pull/2994) *(in review)*
- **[DeepEval](https://github.com/confident-ai/deepeval)** — found and fixed the judge's 1024-token output cap silently truncating responses on thinking-enabled Claude models, surfacing as cryptic invalid-JSON metric errors while thinking tokens were still billed · [Issue #3042](https://github.com/confident-ai/deepeval/issues/3042) → [PR #3043](https://github.com/confident-ai/deepeval/pull/3043) *(in review)*
- **[LiteLLM](https://github.com/BerriAI/litellm)** (56K★, LLM gateway) — traced a user's `/v1/v1/messages` 404 to the one Anthropic passthrough config missing trailing-`/v1` normalization, answered the report, and fixed it · [Discussion #36651](https://github.com/BerriAI/litellm/discussions/36651) → [Issue #36956](https://github.com/BerriAI/litellm/issues/36956) → [PR #36957](https://github.com/BerriAI/litellm/pull/36957) *(in review)*
