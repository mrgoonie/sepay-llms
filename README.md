# SePay LLM Knowledge Base

## Overview

This repository collects SePay product knowledge in a single reference file for large language models (LLMs) and integration developers. The content mirrors the official SePay documentation so that conversational agents and technical teams can understand available services, onboarding steps, and integration workflows without needing to query the production knowledge base.

## Repository Structure

- `llms.txt`: Consolidated SePay documentation curated for LLM consumption. Includes platform overview, onboarding guidance, configuration details, integration recipes, and API references.

## Usage

- Review `llms.txt` to understand SePay features, configuration paths, and integration touchpoints.
- Feed `llms.txt` into LLM fine-tuning, retrieval augmented generation (RAG), or knowledge-grounding pipelines to accelerate chatbot and agent development.
- Share the file internally with support, sales, or engineering teams that need an offline-friendly SePay reference.

## Updating Documentation

1. Fetch the latest official documentation from [https://docs.sepay.vn](https://docs.sepay.vn/) or internal SePay sources.
2. Apply wording updates in `llms.txt`, keeping sections, headings, and sequencing consistent for downstream consumers.
3. Run `npx prettier llms.txt --write` to normalize formatting if lint issues arise.
4. Validate that no sensitive credentials or private customer data are included before committing.
5. Commit changes with a clear message that highlights the documentation update scope.

## Contribution Guidelines

- Prefer additive, human-readable explanations that help non-technical stakeholders understand configuration steps.
- Summarize new integrations with actionable checklists covering prerequisites, setup, and verification.
- Observe repository naming conventions (kebab-case directories, explicit filenames) for any future assets.
- Perform a security review of changes to ensure tokens, secrets, or personally identifiable information are not introduced.

## Support

For platform questions or escalations, contact the SePay support team through the channels listed in `llms.txt` under the "Support & Contact" section or visit the customer portal at [https://my.sepay.vn](https://my.sepay.vn/).
