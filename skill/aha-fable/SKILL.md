---
name: aha-fable
description: Use when the user wants recent notes, meeting notes, AI conversation insights, business problems, or abstract concepts turned into an indirect fable that reveals a higher-order insight, names the hidden principle, and ends with an action-guiding question.
---

# Aha Fable

## Purpose

Turn scattered notes or abstract concepts into a short fable that creates an "aha" moment. The goal is not to explain more clearly; it is to make the reader discover the principle through story, then face one action-guiding question.

## When To Use

Use this skill when the user asks for:

- A fable, parable, allegory, or story-based explanation.
- A hidden principle inside recent notes, flomo, Get Notes, journals, authorized AI conversation excerpts, meeting reflections, or business problems.
- A "wake-up" insight, first-principles blind spot, or higher-order lesson.
- A story followed by a concise reveal and a soul-level action question.

Do not use it for normal summaries, direct analysis, long essays, or motivational quotes.

## Inputs

Use the smallest relevant context:

- Recent notes or user-provided fragments.
- Authorized AI conversation excerpts or summaries.
- The concept to explain, if already known.
- The audience and use case, if specified.
- Any privacy boundary.

If the material is too thin, ask one question: "What recent situation or decision should the fable diagnose?"

## Workflow

1. **Find the hidden pressure.** Read the material and identify one core tension, mistake, or first-principles gap. Do not list many insights.
2. **Name the principle privately.** Decide the concept before writing, but do not reveal it inside the fable.
3. **Choose a concrete world.** Use a setting with objects, work, constraints, and stakes. Avoid the user's exact domain unless asked.
4. **Write the fable.** Include:
   - A protagonist.
   - A clear goal.
   - One mistaken assumption.
   - A real cost.
   - A small observed detail that changes the protagonist's understanding.
   - A final image that lets the reader realize the principle before it is named.
5. **Reveal briefly.** After the fable, name the concept and map 3-5 story elements to the real idea.
6. **Give the operating move.** State one practical behavior change.
7. **End with one soul question.** Make it hard to dodge and directly tied to action.

## Story Rules

- The fable body must not use the concept name or obvious domain jargon.
- The first 80% should be story only, not explanation.
- Use concrete nouns and actions, not abstract teaching.
- Make the protagonist partly wrong, not stupid.
- The reveal should feel earned by the final story detail.
- Keep the explanation shorter than the story.
- Avoid moralizing. Let the story do the work.

## Default Output Format

```markdown
**判断**

[One concise diagnosis of the user's hidden pressure.]

**寓言**

[Story. No direct concept name.]

**揭露**

这个概念叫：[concept name].

[Short mapping from story to concept.]

**行动**

[One behavior change.]

**灵魂反问**

[One question.]
```

## Quality Bar

A good output makes the user want to finish the story before knowing the answer. If the fable could be replaced by a direct explanation with no loss, rewrite it.

Read `references/example-output.md` when you need a calibration example.
