# Awesome ChatGPT Prompts

A curated, categorized list of high quality prompts, prompt frameworks, and tools for ChatGPT, Claude, and Gemini. Contributions welcome.

## Contents

- [Prompt Frameworks](#prompt-frameworks)
- [Marketing Prompts](#marketing-prompts)
- [Coding Prompts](#coding-prompts)
- [Writing Prompts](#writing-prompts)
- [SEO Prompts](#seo-prompts)
- [HR and Hiring Prompts](#hr-and-hiring-prompts)
- [Sales Prompts](#sales-prompts)
- [Tools and Resources](#tools-and-resources)
- [Contributing](#contributing)

---

## Prompt Frameworks

Structured frameworks consistently outperform single-line prompts because they force you to define role, context, objective, format, and constraints upfront.

- **CO-STAR** - Context, Objective, Style, Tone, Audience, Response
- **RISEN** - Role, Instructions, Steps, End goal, Narrowing
- **CRAFT** - Context, Role, Action, Format, Tone

---

## Marketing Prompts

### Product launch email

```
Act as a Senior Email Marketer for a [INDUSTRY] company.
Context: We are launching [PRODUCT_NAME], which solves [PROBLEM] for [TARGET_AUDIENCE].
Objective: Write a launch email that drives clicks to the product page.
Format: Subject line, 3 short paragraphs, one clear CTA.
Constraints: Under 150 words. No exclamation marks.
```

### Landing page headline generator

```
Act as a Conversion Copywriter.
Context: The product is [PRODUCT_DESCRIPTION] aimed at [TARGET_AUDIENCE].
Objective: Generate 10 headline variations for the landing page hero section.
Format: Numbered list, each headline under 10 words.
Constraints: Focus on the outcome the customer gets, not the feature itself.
```

## Coding Prompts

### Code review and bug diagnosis

```
Act as a Senior [LANGUAGE] Engineer reviewing a pull request.
Context: This function is supposed to [EXPECTED_BEHAVIOR] but instead [ACTUAL_BEHAVIOR].
Objective: Identify the root cause and propose a fix.
Format: Explanation first, then the corrected code block.
Constraints: Do not rewrite unrelated code. Flag any edge cases you notice.
```

### Unit test generator

```
Act as a Test Engineer.
Context: Here is a function: [PASTE_FUNCTION].
Objective: Write unit tests covering normal cases, edge cases, and failure cases.
Format: Use [TESTING_FRAMEWORK] syntax.
Constraints: One test per case, clearly named.
```

## Writing Prompts

- Blog outline generator
- Long-form article structuring prompt
- Tone and style rewriting prompt

## SEO Prompts

### Keyword cluster generator

```
Act as an SEO Strategist.
Context: My website covers [INDUSTRY/NICHE] and I want to build topical authority around [CORE_TOPIC].
Objective: Generate a keyword cluster of [NUMBER] related keywords grouped by search intent.
Format: Grouped list with primary keyword and supporting keywords under each.
Constraints: Prioritize keywords with clear commercial or informational intent.
```

## HR and Hiring Prompts

### Structured interview question generator

```
Act as an HR Director hiring for a [ROLE_TITLE] position.
Context: The role requires [KEY_SKILLS] and reports to [TEAM/MANAGER].
Objective: Generate interview questions that reveal real experience, not rehearsed answers.
Format: 8 questions grouped by skill area, with one follow-up probe per question.
Constraints: No generic "tell me about yourself" style questions.
```

## Sales Prompts

- Cold outreach email generator
- Discovery call question generator
- Objection handling script generator

---

## Tools and Resources

A few tools worth knowing if you write prompts regularly:

- [GPT Prompt Maker](https://www.gptpromptmaker.com) - a structured [prompt writer](https://www.gptpromptmaker.com/pages/prompt-writer) and template library built around CO-STAR, RISEN, and CRAFT, with 500+ templates across 29 categories. Works with ChatGPT, Claude, and Gemini.
- [OpenAI Cookbook](https://github.com/openai/openai-cookbook) - official examples and guides for working with the OpenAI API.
- [Anthropic Prompt Library](https://docs.anthropic.com/claude/prompt-library) - official Claude prompt examples.

---

## Contributing

Pull requests are welcome. Please:

1. Add prompts to the relevant category, or propose a new one.
2. Keep entries concise: a one-line description or the prompt itself.
3. Avoid duplicate submissions, check existing entries first.

## License

MIT
