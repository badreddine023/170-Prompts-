# 📚 Ultimate ChatGPT Prompts - User Guide

> Your complete guide to getting maximum value from this prompt collection.

---

## 🚀 Quick Start (5 Minutes)

### Step 1: Choose Your Category
Browse the `/prompts` folder and select a category:
- 📢 **Marketing** - Social media, email, landing pages
- 💻 **Programming** - Code review, debugging, architecture
- ⚡ **Productivity** - Planning, decisions, meetings
- 🧠 **Personal** - Life coaching, habits, conversations
- 💼 **Business** - Business models, competitors, pitches
- 🎨 **Creative** - Stories, branding, video scripts

### Step 2: Open the JSON File
Each category has a `[category]_prompts.json` file with 3 prompts.

### Step 3: Copy the Prompt
Find the `"prompt"` field and copy the entire text.

### Step 4: Customize the Brackets
Replace all `[BRACKETED TEXT]` with your specific information.

### Step 5: Paste into ChatGPT
Use GPT-4 or GPT-4o for best results. Claude and Gemini also work well.

---

## 📖 Detailed Usage Guide

### Understanding the JSON Structure

Each prompt follows this format:

```json
{
  "id": "MKT-001",           // Unique identifier
  "title": "Prompt Name",    // What it does
  "category": "Marketing",   // Category
  "description": "...",      // Short description
  "prompt": "...",           // THE ACTUAL PROMPT TO USE
  "example_output": "..."    // Sample result
}
```

### Customization Tips

#### 1. Fill in ALL Brackets
Every `[BRACKET]` needs your input:
```
❌ "Create content for [TOPIC]"
✅ "Create content for sustainable fashion for millennials"
```

#### 2. Be Specific
More detail = better results:
```
❌ [YOUR BUSINESS] = "my company"
✅ [YOUR BUSINESS] = "B2B SaaS startup selling project management software to marketing teams, $50K MRR, 200 customers"
```

#### 3. Add Context
Include relevant background:
```
❌ [TARGET AUDIENCE] = "customers"
✅ [TARGET AUDIENCE] = "Marketing managers at mid-size companies (50-500 employees) who are frustrated with complex tools and want simplicity"
```

---

## 🎯 Best Practices

### For Best Results:

1. **Use GPT-4 or GPT-4o**
   - These prompts are optimized for advanced models
   - GPT-3.5 will work but with reduced quality

2. **Don't Truncate**
   - Copy the ENTIRE prompt, including all sections
   - The structure is designed for comprehensive outputs

3. **Iterate**
   - First output not perfect? Ask for refinements
   - "Make the tone more casual" or "Expand section 3"

4. **Save Your Customized Versions**
   - Once you fill in brackets, save for reuse
   - Build a personal library of ready-to-go prompts

### Common Mistakes to Avoid:

❌ **Leaving brackets unfilled**
- AI will literally output "[YOUR PRODUCT]"

❌ **Being too vague**
- "Make it good" → "Make it conversational, use short sentences, include 2 examples"

❌ **Ignoring the example output**
- Review it to understand what to expect

❌ **Not iterating**
- First draft is a starting point, not final product

---

## 📂 Category Deep Dives

### 📢 Marketing Prompts

**Best for:**
- Content creators
- Marketing managers
- Entrepreneurs
- Social media managers

**Included Prompts:**
1. **Viral Social Media Hook Generator** - Create scroll-stopping content
2. **Email Sequence Architect** - Design complete email campaigns
3. **Landing Page Copy Framework** - High-converting page copy

**Pro Tip:** Combine prompts! Use the Hook Generator for email subject lines.

---

### 💻 Programming Prompts

**Best for:**
- Software developers
- Tech leads
- CTOs
- DevOps engineers

**Included Prompts:**
1. **Senior Code Reviewer** - Get expert-level code feedback
2. **Architecture Decision Document** - Create professional ADRs
3. **Debug Detective** - Systematic debugging assistance

**Pro Tip:** Paste actual code snippets for specific, actionable feedback.

---

### ⚡ Productivity Prompts

**Best for:**
- Executives
- Managers
- Entrepreneurs
- Anyone feeling overwhelmed

**Included Prompts:**
1. **Weekly Planning Architect** - Optimize your schedule
2. **Decision Matrix Generator** - Make better decisions
3. **Meeting Optimizer** - Fix unproductive meetings

**Pro Tip:** Use Weekly Planning every Sunday for best results.

---

### 🧠 Personal Development Prompts

**Best for:**
- Anyone seeking growth
- Career changers
- People building habits
- Those facing difficult conversations

**Included Prompts:**
1. **Life Coach Session** - Deep personal coaching
2. **Habit Architect** - Build lasting habits
3. **Difficult Conversation Prep** - Navigate tough talks

**Pro Tip:** Journal your answers to the coaching questions.

---

### 💼 Business Prompts

**Best for:**
- Founders
- Business strategists
- Product managers
- Investors

**Included Prompts:**
1. **Business Model Canvas Generator** - Complete business model
2. **Competitor Analysis Deep Dive** - Strategic intelligence
3. **Pitch Deck Script Writer** - Fundraising content

**Pro Tip:** Update your Business Model Canvas quarterly.

---

### 🎨 Creative Prompts

**Best for:**
- Writers
- Content creators
- Brand managers
- YouTubers

**Included Prompts:**
1. **Story Plot Generator** - Complete narrative structures
2. **Brand Voice Guide** - Comprehensive brand guidelines
3. **YouTube Script Writer** - Retention-optimized scripts

**Pro Tip:** Use the Brand Voice Guide before any content creation.

---

## 🔧 Troubleshooting

### "The output is too generic"
**Solution:** Add more specific details in the brackets. Include numbers, names, and concrete examples.

### "The output is too long/short"
**Solution:** Add length instructions: "Keep each section under 100 words" or "Provide detailed explanations of at least 500 words per section"

### "The AI didn't follow the format"
**Solution:** Add "Follow the exact format provided" at the end of your prompt.

### "I'm getting errors or refusals"
**Solution:** Some prompts may trigger content filters. Rephrase sensitive topics or use a different model.

---

## 💡 Advanced Techniques

### Prompt Chaining
Use outputs from one prompt as inputs for another:
1. Generate Business Model Canvas
2. Use the customer segment for Competitor Analysis
3. Use insights for Pitch Deck

### Role Stacking
Add additional context to any prompt:
```
"Before we begin, note that I'm a [YOUR ROLE] at a [COMPANY TYPE] 
targeting [AUDIENCE]. Keep this context in mind throughout."
```

### Output Formatting
Request specific formats:
```
"Format your response as:
- Markdown with headers
- Bullet points for lists
- Code blocks for examples
- Tables for comparisons"
```

---

## 📞 Support

**Questions?** Open an issue on GitHub.

**Want more prompts?** Check out our premium collection on Gumroad with 50+ additional prompts, monthly updates, and priority support.

---

*User Guide v1.0 | Last Updated: December 2025*
