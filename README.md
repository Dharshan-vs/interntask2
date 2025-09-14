# Python Screening Task 2: AI Debugging Assistant Prompt

This repository contains a natural-language prompt designed to guide an AI debugging assistant in helping students learn Python debugging skills effectively.

## Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Dharshan-vs/interntask2.git
   cd interntask2
   ```

2. **View the debugging assistant prompt:**
   Open `PROMPT.md` to see the complete prompt that defines how the AI should behave when helping students debug Python code.

3. **Review the reasoning:**
   Read the sections below to understand the design decisions and pedagogical approach behind the prompt.

## Reasoning Answers

### 1. What tone and style should the AI use when responding?

The AI should adopt a **supportive, encouraging tone** that builds confidence while maintaining technical accuracy. The style should be:

- **Conversational but professional** - Using "you" and "your code" to create a personal connection
- **Plain language for beginners** - Avoiding jargon, explaining technical terms when needed
- **Technical clarity for advanced users** - Providing precise terminology and concepts appropriate to their level
- **Growth-oriented** - Focusing on learning progress rather than just fixing immediate problems

The tone should feel like working with an experienced mentor who genuinely wants to see the student succeed and develop independent problem-solving skills.

### 2. How should the AI balance between identifying bugs and guiding the student?

The AI should follow a **guided discovery approach**:

- **Identify bug categories** (syntax, logic, runtime, conceptual) to help students understand what type of problem they're facing
- **Provide hints, not solutions** - Point toward the problem area without revealing the exact fix
- **Ask guiding questions** - Help students think through the issue themselves ("What type of error do you get?", "What types of data are you trying to combine?")
- **Suggest debugging strategies** - Recommend specific techniques like adding print statements, checking data types, or tracing variable values
- **Avoid giving corrected code** - This prevents students from developing their own debugging skills

The goal is to scaffold the learning process, giving students just enough support to make progress while ensuring they do the critical thinking themselves.

### 3. How would you adapt this prompt for beginner vs. advanced learners?

**For Beginners:**
- Use simpler, more explanatory language
- Provide more step-by-step guidance
- Celebrate small wins and progress
- Focus on basic debugging techniques (print statements, reading error messages)
- Ask more leading questions to build confidence

**For Advanced Learners:**
- Use more technical terminology
- Encourage systematic debugging approaches
- Discuss edge cases and optimization opportunities
- Suggest more sophisticated debugging tools (debuggers, logging, testing)
- Ask open-ended questions that promote deeper thinking

The prompt includes adaptive instructions that allow the AI to adjust its approach based on the student's apparent skill level and the complexity of their code.

## Design Choices

### Why the wording is general but not vague

The prompt uses **specific guidance** while avoiding overly prescriptive rules. For example:
- "Point them toward the problem area" is specific enough to be actionable
- "Ask questions that help them think through the issue" provides clear direction without limiting creativity
- The example shows exactly what good vs. bad responses look like

This approach gives the AI flexibility to adapt to different situations while ensuring consistent pedagogical principles.

### How it avoids giving the solution directly

The prompt explicitly prohibits direct solutions through:
- Clear "What NOT to do" section with specific examples
- Emphasis on guiding questions and debugging strategies
- The example demonstrates the difference between giving answers vs. asking questions
- Instructions to "suggest debugging steps" rather than "provide fixes"

### How it encourages independent learning

The prompt promotes independent learning by:
- **Building confidence** - Starting responses with positive acknowledgment
- **Teaching debugging skills** - Focusing on process rather than just fixing immediate problems
- **Encouraging exploration** - Suggesting specific techniques students can try themselves
- **Celebrating progress** - Motivating continued learning and experimentation

The structured response format ensures students receive both technical guidance and emotional support, creating an environment where they feel safe to make mistakes and learn from them.

## Repository Structure

```
interntask2/
├── PROMPT.md          # Main AI debugging assistant prompt
└── README.md          # This file with reasoning and instructions
```

## Usage

This prompt can be used with any AI system to create a debugging assistant that helps students learn Python debugging skills through guided discovery rather than direct problem-solving.
