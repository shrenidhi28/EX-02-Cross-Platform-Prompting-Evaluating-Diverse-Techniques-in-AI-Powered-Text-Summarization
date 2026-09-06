
# EX-03-Prompt-Structures-for-Text-Summarization

## Objective

To design and improve prompts using different prompt structures and understand how adding role, context, constraints, and output-format instructions can improve the quality of Generative AI responses.

---

# Application Selected

## Text Summarization

### Scenario

A student wants to summarize a technical article on **Blockchain Technology** for quick understanding and revision.

The prompt is progressively enhanced using:

1. Basic Prompt
2. Role Prompt
3. Context Prompt
4. Constraint Prompt
5. Output Format Prompt

The objective is to observe how each additional prompt structure improves the final output.

---

# Step 1: Basic Prompt

The basic prompt contains only the main task.

### Prompt

```text
Summarize the following article about Blockchain Technology.

Article:
[Paste the article here]
````

### Expected Output

The AI generates a general summary of the article without specific instructions about:

* Audience
* Length
* Style
* Important points
* Output format

---

# Step 2: Role Prompt

A specific role is assigned to the AI to make the response more targeted.

### Prompt

```text
Act as a Computer Science professor.

Summarize the following article about Blockchain Technology.

Article:
[Paste the article here]
```

### Improvement

The AI is given a professional perspective and is more likely to explain the topic in an educational and technically appropriate manner.

---

# Step 3: Context Prompt

Additional information about the user and purpose is provided.

### Prompt

```text
Act as a Computer Science professor.

You are helping an undergraduate engineering student understand Blockchain Technology for an academic assignment and examination preparation.

Summarize the following article about Blockchain Technology.

Focus on the important concepts that an engineering student should understand.

Article:
[Paste the article here]
```

### Improvement

The AI now understands:

* Who the user is
* Why the summary is required
* What information is important
* The educational context

---

# Step 4: Constraint Prompt

Specific restrictions are added to control the response.

### Prompt

```text
Act as a Computer Science professor.

You are helping an undergraduate engineering student understand Blockchain Technology for an academic assignment and examination preparation.

Summarize the following article.

Follow these constraints:
- Keep the summary between 100 and 150 words.
- Use simple and clear English.
- Include the definition of blockchain.
- Explain how blockchain works.
- Mention decentralization.
- Mention blocks and hashing.
- Mention consensus mechanisms.
- Include important applications.
- Do not add information that is not supported by the article.
- Avoid unnecessary technical details.

Article:
[Paste the article here]
```

### Improvement

The constraints make the output more:

* Focused
* Concise
* Relevant
* Consistent
* Suitable for students

---

# Step 5: Output Format Prompt

The final prompt specifies exactly how the answer should be presented.

### Final Prompt

```text
Act as a Computer Science professor who specializes in Blockchain Technology.

You are helping an undergraduate engineering student understand Blockchain Technology for an academic assignment and examination preparation.

Summarize the following technical article.

Follow these constraints:
- Keep the summary between 100 and 150 words.
- Use simple and clear English.
- Include only information supported by the article.
- Focus on the most important concepts.
- Avoid unnecessary technical details.
- Make the explanation suitable for an undergraduate engineering student.

Include the following concepts if they are discussed in the article:
- Definition of Blockchain
- Decentralization
- Blocks
- Hashing
- Consensus
- Blockchain applications

Use the following output format:

## Summary

[Write the summary in 100–150 words]

## Key Concepts

- Concept 1: Brief explanation
- Concept 2: Brief explanation
- Concept 3: Brief explanation
- Concept 4: Brief explanation
- Concept 5: Brief explanation

## One-Line Takeaway

[Give the main idea of the article in one sentence]

Article:
[Paste the article here]
```

---

# Prompt Evolution

The prompt evolves progressively:

```text
Basic Prompt
     ↓
Add Role
     ↓
Add Context
     ↓
Add Constraints
     ↓
Add Output Format
     ↓
Final Prompt
```

---

# Comparison of Prompt Structures

| Prompt Structure     | Main Purpose                    | Improvement                      |
| -------------------- | ------------------------------- | -------------------------------- |
| Basic Prompt         | Defines the task                | Provides a general response      |
| Role Prompt          | Assigns expertise/persona       | Makes the response more targeted |
| Context Prompt       | Provides background and purpose | Makes the response more relevant |
| Constraint Prompt    | Controls content and length     | Makes the response focused       |
| Output Format Prompt | Defines response structure      | Makes the output organized       |

---

# Prompt Construction Formula

A useful way to construct a high-quality prompt is:

```text
ROLE
  +
CONTEXT
  +
TASK
  +
CONSTRAINTS
  +
OUTPUT FORMAT
  =
EFFECTIVE FINAL PROMPT
```

---

# Output Comparison

## Basic Prompt Output

The response may be:

* General
* Less structured
* Variable in length
* Not specifically targeted to students

## Role Prompt Output

The response becomes more:

* Professional
* Educational
* Technically focused

## Context Prompt Output

The response becomes:

* More relevant to the student's needs
* Better targeted
* More academically useful

## Constraint Prompt Output

The response becomes:

* Concise
* Focused
* Consistent
* Easier to evaluate

## Output Format Prompt Output

The final response becomes:

* Well organized
* Easy to read
* Easy to revise
* Suitable for academic use

---

# Evaluation Criteria

The prompts can be evaluated using:

| Criteria    | Basic | Role | Context | Constraint | Output Format |
| ----------- | ----: | ---: | ------: | ---------: | ------------: |
| Relevance   |    /5 |   /5 |      /5 |         /5 |            /5 |
| Accuracy    |    /5 |   /5 |      /5 |         /5 |            /5 |
| Clarity     |    /5 |   /5 |      /5 |         /5 |            /5 |
| Conciseness |    /5 |   /5 |      /5 |         /5 |            /5 |
| Structure   |    /5 |   /5 |      /5 |         /5 |            /5 |
| Usefulness  |    /5 |   /5 |      /5 |         /5 |            /5 |

---

# Observations

### Basic Prompt

Provides a simple summary but gives the AI considerable freedom in deciding the length, style and content.

### Role Prompt

Assigning the role of a Computer Science professor makes the response more educational and technically focused.

### Context Prompt

Providing the student's purpose and background helps the AI generate a response that is more relevant to academic requirements.

### Constraint Prompt

Adding word limits, required concepts and content restrictions provides better control over the generated response.

### Output Format Prompt

Specifying the desired structure produces a more organized and readable response.

---

# Result

The prompts were successfully developed progressively from a **Basic Prompt** to a **Final Structured Prompt**.

The experiment demonstrates that adding **Role, Context, Constraints and Output Format** instructions provides greater control over Generative AI output and improves its relevance, clarity, consistency and usefulness.

---

# Conclusion

Prompt engineering is an iterative process. A simple instruction can be progressively enhanced by adding information about the **role of the AI, context of the task, constraints and expected output format**.

The final prompt provides significantly more control over the generated response than the basic prompt. Therefore, structured prompting can be used to obtain more **accurate, relevant, consistent and user-defined outputs** from Generative AI systems.

---

# Final Prompt

```text
Act as a Computer Science professor who specializes in Blockchain Technology.

You are helping an undergraduate engineering student understand Blockchain Technology for an academic assignment and examination preparation.

Summarize the following technical article.

Follow these constraints:
- Keep the summary between 100 and 150 words.
- Use simple and clear English.
- Include only information supported by the article.
- Focus on the most important concepts.
- Avoid unnecessary technical details.
- Make the explanation suitable for an undergraduate engineering student.

Include the following concepts if they are discussed in the article:
- Definition of Blockchain
- Decentralization
- Blocks
- Hashing
- Consensus
- Blockchain applications

Use the following output format:

## Summary

[Write the summary in 100–150 words]

## Key Concepts

- Concept 1: Brief explanation
- Concept 2: Brief explanation
- Concept 3: Brief explanation
- Concept 4: Brief explanation
- Concept 5: Brief explanation

## One-Line Takeaway

[Give the main idea of the article in one sentence]

Article:
[Paste the article here]
```

# Result

**Thus, prompts were successfully designed and progressively enhanced from a basic prompt to a final structured prompt by incorporating Role, Context, Constraints, and Output Format. The final prompt produced a more controlled, relevant, clear and user-defined output for text summarization.**

