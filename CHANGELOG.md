# Changelog

## Unreleased

- Added Claude plugin manifests, `.claude-plugin/plugin.json` and `.claude-plugin/marketplace.json`, so the same skills install in Claude. The skills are unchanged.
- README.md and TESTING.md now cover installing in Claude as well as Grok Bot.

## 0.1.1 (Grok Bot edition, unreleased)

First release from this repository. It has the same seven skills and website workflows as FindAffiliates 0.1.1 for the OpenAI plugin directory, adapted for Grok Bot and other hosts that read the Cursor plugin format.

- The manifest is `.cursor-plugin/plugin.json`. OpenAI-only metadata, `extensions.com.openai` and each skill's `agents/openai.yaml`, is not included.
- Skills refer to the agent's available browser instead of "this chat".
- Excluded program categories are named directly instead of by reference to OpenAI's plugin policies, and the skills also follow the host platform's usage policies.
- The account skill lets the user sign in by taking control of the agent's browser, and says when a persistent browser keeps that session.
- The logo is the existing FindAffiliates mark, unscaled and unrecolored, centered on a white 640x640 plate.
