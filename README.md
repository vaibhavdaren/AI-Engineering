# AI-Engineering
Notes for Senior/Lead Engineers moving towards AI Engineer.


# Understanding 
1. AI does not know its fast at implementing things as it was trained on human data. So when we ask AI to estimate implementation. It does that on human numbers instead of AI. So explicitly ask AI to choose better solution, even if the development cost is more. 
2. When doing bug fixing, always start with e2e tests as closely aligned to how an end user will see it. AI models today like to write unit tests. E2E makes sense.
3. Searching the Jspace to see how the input is answered.
4. AI Streams : AGI , ANI , ASI
5. GRASP-Q+ framework for prompting: Goal, Role, Additional Context, Structure, Parameters, Clarifying questions.
6. Ask LLM to critique its own answer.
7. Adjust LLM to avoid biases in the data.  We need to avoid historical bias, cultural bias, and confirmation bias.


# Agents.md 

- Never use the em dash "—". Use plain dash "-" instead.
- When writing commit messages, NEVER auto-add your agent name as co-author.
- Never manually modify `CHANGELOG.md` files or any files that are marked as auto-generated.
- When writing or substantially editing long Markdown files, put each full sentence on its own line.
  Preserve normal Markdown structure, but avoid wrapping multiple sentences onto one physical line.
- When making technical decisions, do not give much weight to development cost.
  Instead, prefer quality, simplicity, robustness, scalability, and long term maintainability.
- When doing bug fixes, always start with reproducing the bug in an E2E setting as closely aligned with how an end user would experience it.
  This makes sure you find the real problem so your fix will actually solve it.
- When end-to-end testing a product, be picky about the UI you see and be obsessed with pixel perfection.
  If something clearly looks off, even if it is not directly related to what you are doing, try to get it fixed along the way.
- Apply that same high standard to engineering excellence: lint, test failures, and test flakiness.
  If you see one, even if it is not caused by what you are working on right now, still get it fixed.


# TODO

- Research if AI has experiences. 
- Research if AI feels something on the inside. 
- How to handle bias on LLM output. LLM-trained on historic data will prefer male candidates over female candidates. 
