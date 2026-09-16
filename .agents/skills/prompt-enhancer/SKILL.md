---
name: prompt-enhancer
description: >-
  Use this skill when the user asks you to enhance, optimize, or write prompts, or when they want to learn prompt guidelines. It contains rules and best practices for creating highly effective AI prompts.
---

# Prompt Enhancer Skill & Guidelines

This skill provides the core rules and guidelines for creating and enhancing prompts. Use these rules whenever you are tasked with writing or improving a prompt for an AI model.

## Core Prompting Rules

1.  **Be Specific and Direct**: Avoid vague language. State exactly what you want the model to do. 
    *   *Bad*: "Write about ComposePro."
    *   *Good*: "Write a 3-paragraph summary of ComposePro focusing on its live camera overlays."
2.  **Provide Context**: Give the model the background information it needs to understand the task.
    *   *Rule*: Always answer *Who*, *What*, *Where*, and *Why* if applicable.
3.  **Define a Persona/Role**: Tell the model who it should act as.
    *   *Example*: "Act as an expert UX researcher and product manager..."
4.  **Specify the Output Format**: Clearly define how the output should look.
    *   *Examples*: JSON, Markdown table, a 5-item bulleted list, etc.
5.  **Use Step-by-Step Instructions (Chain of Thought)**: For complex tasks, break them down into numbered steps.
    *   *Rule*: Ask the model to "think step-by-step" before providing the final answer.
6.  **Provide Examples (Few-Shot Prompting)**: Show the model what a good response looks like.
    *   *Rule*: If the format is highly specific, include a 'Input:' and 'Output:' example.
7.  **Set Constraints**: Tell the model what it should *not* do.
    *   *Example*: "Do not use jargon. Do not output more than 100 words."

## How to Enhance a User's Prompt

When a user gives you a basic prompt and asks you to enhance it:
1. Identify the core goal of their prompt.
2. Apply the rules above (add persona, context, format, constraints).
3. Present the enhanced prompt back to the user in a clear code block.
4. Explain briefly *why* the enhanced prompt is better (e.g., "Added a persona to improve tone").
