# Claude.ai Cheat Sheet

## Basic Prompting

### Clear Instructions
```
Write a [type] about [topic] that is [length] and focuses on [specific aspects].
Example: "Write a blog post about artificial intelligence that is 500 words and focuses on practical applications in healthcare."
```

### Role-Based Prompts
```
Act as a [role] and [action].
Example: "Act as a financial advisor and analyze this investment portfolio."
```

### Format Specification
```
Present the response in [format] with [specific elements].
Example: "Present the response in a table with columns for Category, Description, and Priority."
```

## Advanced Techniques

### Step-by-Step Analysis
```
1. First, analyze [aspect 1]
2. Then, consider [aspect 2]
3. Finally, provide [conclusion/recommendation]
Example: 
1. First, analyze the current market conditions
2. Then, consider competitive factors
3. Finally, provide recommendations for market entry
```

### Chain of Thought
```
Let's solve this step by step:
1. Let's start with [initial step]
2. Based on that, we can [next step]
3. Therefore, [conclusion]
```

### Few-Shot Examples
```
Here are some examples:
Input: [example input 1]
Output: [example output 1]

Input: [example input 2]
Output: [example output 2]

Now, process this:
Input: [actual input]
```

## Special Commands

### File Operations
```
- Read file: Use window.fs.readFile API
- List directory: List available directories and files
- Create/Update files: Push changes to repositories
```

### Browser Control
```
- Navigate: Use puppeteer_navigate to visit URLs
- Screenshot: Capture page screenshots
- Click: Interact with page elements
```

### GitHub Integration
```
- Create repositories
- Push files
- Create issues/PRs
- Fork repositories
```

## Best Practices

### Be Specific
✅ DO:
- Provide clear context
- Specify desired output format
- Include relevant details

❌ DON'T:
- Use vague instructions
- Assume context
- Mix multiple unrelated requests

### Use Structured Prompts
✅ DO:
- Break down complex tasks
- Use numbered lists
- Specify constraints

❌ DON'T:
- Write wall of text
- Combine multiple questions
- Leave requirements ambiguous

### Handle Iterations
✅ DO:
- Build on previous context
- Reference earlier responses
- Clarify misunderstandings

❌ DON'T:
- Restart from scratch
- Ignore previous context
- Leave ambiguities unresolved

## Response Control

### Output Format
```
Format the response as:
- Bullet points
- Table
- Numbered list
- Markdown
```

### Length Control
```
Provide a [brief/detailed] response in [X] words/paragraphs.
Focus on [key aspects] only.
```

### Style Control
```
Write in a [formal/casual/technical] style.
Use [simple/advanced] language suitable for [audience].
```

## Common Use Cases

### Content Creation
```
Write a [blog post/article/script] about [topic]
Include:
- Key points
- Examples
- Conclusions
```

### Analysis
```
Analyze [subject] considering:
1. Current situation
2. Key factors
3. Recommendations
```

### Code Review
```
Review this code for:
- Best practices
- Performance
- Security
- Readability
```

## Tips & Tricks

1. **Start Broad, Then Refine**
   - Begin with general request
   - Use follow-up questions
   - Iterate based on responses

2. **Provide Examples**
   - Show desired format
   - Include sample inputs/outputs
   - Demonstrate edge cases

3. **Use System Tags**
   - Set context with <system> tags
   - Define roles clearly
   - Specify constraints

4. **Handle Complex Tasks**
   - Break into subtasks
   - Use step-by-step approach
   - Build on intermediate results

## Troubleshooting

### If Responses Are Too Long
- Specify word/length limit
- Focus on key aspects
- Request summary format

### If Responses Are Too Technical
- Specify target audience
- Request simpler language
- Ask for examples

### If Context Is Lost
- Reference previous messages
- Summarize context
- Maintain conversation thread

## Quick Reference

### Common Tags
```
<system> - System instructions
<user> - User messages
<assistant> - Claude's responses
```

### Format Controls
```
# Headers
* Bullets
1. Numbered lists
| Tables |
```

### Special Functions
```
fs.readFile() - Read files
puppeteer_* - Browser control
artifact_* - Create artifacts
```

## Remember
- Be clear and specific
- Provide context
- Use appropriate format
- Build iteratively
- Learn from responses