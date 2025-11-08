# Super Analyst 2.0 - Installation Guide

## 📦 Package Information

**File:** super-analyst-v2.0.skill  
**Version:** 2.0  
**Release Date:** October 26, 2025  
**Size:** ~24 KB (compressed)  
**Status:** Production Ready

---

## ✅ Prerequisites

Before installing Super Analyst 2.0, ensure you have:

1. **prompt-house-local MCP Server** ✅
   - All 12 framework prompts must be installed
   - Verified available in previous conversation

2. **sequential-thinking MCP Server** ✅
   - For deep thinking at decision points
   - Required for Stage 2 and Stage 4

3. **Web Search Capability** ✅
   - Built-in web_search tool (no additional setup)
   - For intelligence gathering in Stage 3

---

## 📥 Installation Steps

### Method 1: Direct Installation (Recommended)

1. Download `super-analyst-v2.0.skill` file
2. In Claude, go to Skills management
3. Click "Import Skill" or drag and drop the .skill file
4. Verify installation by asking: "What is Super Analyst 2.0?"

### Method 2: Manual Installation

1. Unzip `super-analyst-v2.0.skill`
2. Copy contents to Claude's skills directory
3. Restart Claude if necessary
4. Verify installation

---

## 🧪 Verification & Testing

### Quick Test - Level 1 (Simple)

**Ask:** "What is SWOT analysis? Explain it to me."

**Expected:**
- Claude recognizes as Level 1 question
- Skips intelligence gathering (no search needed)
- Uses appropriate frameworks (likely First Principles + Socratic)
- Delivers conceptual explanation in ~1-2 minutes

### Medium Test - Level 2

**Ask:** "Analyze Tesla's competitive advantages in the EV market"

**Expected:**
- Claude recognizes as Level 2 question
- Stage 2: Plans 2-4 searches (Sequential Thinking shown collapsed)
- Stage 3: Executes searches with progress indicators
- Stage 4: Selects SWOT or similar framework
- Delivers analysis in ~3-6 minutes

### Complex Test - Level 3

**Ask:** "Should a mid-sized US retailer enter the Indian e-commerce market? Provide comprehensive strategic assessment."

**Expected:**
- Claude recognizes as Level 3 question
- Stage 2: Plans 5-10 searches (Sequential Thinking collapsed)
- Stage 3: Comprehensive intelligence gathering
- Stage 4: Selects 2-4 frameworks (Sequential Thinking collapsed)
- Delivers complete strategic report in ~10-20 minutes

---

## 🎯 What to Expect

### User Experience Flow

```
1. You ask a question
   ↓
2. Claude assesses complexity (Level 1/2/3)
   ↓
3. [If research needed] Intelligence gathering with progress
   ↓
4. Framework selection with reasoning
   ↓
5. Structured analysis execution
   ↓
6. Comprehensive report with recommendations
```

### Visual Indicators

**Stage Markers:**
- 👋 Initial greeting with complexity level
- 🔍 Intelligence planning (with collapsed thinking)
- 🌐 Intelligence gathering (with progress: [1/6], [2/6]...)
- 🎯 Framework selection (with collapsed thinking)
- 📊 Structured analysis
- 📌 Completion summary

**Collapsed Sections:**
- Sequential Thinking processes are collapsed by default
- Click to expand if you want to see the reasoning
- Main workflow stays clean and focused

---

## 📚 Documentation Structure

After installation, you'll have access to:

```
super-analyst-v2.0/
├── SKILL.md (Main workflow - READ THIS FIRST)
├── README.md (Quick overview)
├── CHANGELOG.md (Version history)
├── UPGRADE-SUMMARY.md (What changed from v1.0)
├── INSTALLATION-GUIDE.md (This file)
├── references/
│   ├── framework-mapping.md (Framework profiles)
│   ├── search-strategy-guide.md (Search best practices)
│   ├── sequential-thinking-prompts.md (Thinking templates)
│   └── usage-examples.md (10 complete examples)
└── scripts/
    └── framework_selector.py (Optional utility)
```

**Start with:** SKILL.md for complete workflow understanding

---

## 💡 Usage Tips

### For Best Results

1. **Be Specific**
   ```
   ❌ "Tell me about the market"
   ✅ "Analyze the Indian e-commerce market size and growth trends"
   ```

2. **Provide Context**
   ```
   ❌ "Should we do this?"
   ✅ "Should our mid-sized US retailer enter Indian e-commerce?"
   ```

3. **Indicate Depth**
   ```
   Quick: "Brief analysis of..."
   Deep: "Comprehensive assessment of..."
   ```

### Common Use Cases

- **Business Strategy:** Market entry, competitive analysis, strategic planning
- **Problem Solving:** Root cause analysis, process improvement
- **Innovation:** Product development, business model innovation
- **Decisions:** Investment evaluation, resource allocation, prioritization

---

## 🔧 Troubleshooting

### Issue: Claude doesn't recognize the skill

**Solution:**
- Verify installation completed
- Restart Claude
- Try asking: "Use Super Analyst to analyze..."

### Issue: No intelligence gathering happening

**Possible causes:**
- Question is conceptual (Level 1) - no search needed
- Web search not available - check connectivity
- User explicitly said "don't search" or "use only your knowledge"

**Verify:** Ask a question that clearly needs research like "What is Tesla's current market share in China?"

### Issue: Framework selection seems off

**Note:** Framework selection uses Sequential Thinking to make optimal choices. If you disagree:
- Expand the collapsed thinking to see reasoning
- You can explicitly request specific frameworks
- Provide feedback on what framework would be better

### Issue: Analysis too short/long

**Solutions:**
- For shorter: Ask for "brief analysis" or "quick assessment"
- For longer: Ask for "comprehensive analysis" or "deep dive"
- For specific: "Focus on [specific aspect]"

---

## 📊 Performance Expectations

| Complexity | Time | Searches | Frameworks | Output Length |
|-----------|------|----------|------------|---------------|
| Level 1 | 1-2 min | 0-1 | 1-2 | Brief |
| Level 2 | 3-6 min | 2-4 | 1-2 | Moderate |
| Level 3 | 10-20 min | 5-10 | 2-4 | Comprehensive |

---

## 🆘 Support

### Getting Help

1. **Read Documentation**
   - SKILL.md for workflow understanding
   - usage-examples.md for similar scenarios
   - Specific guides for search/thinking strategies

2. **Check Examples**
   - 10 complete examples in usage-examples.md
   - Cover Level 1, 2, and 3 scenarios

3. **Experiment**
   - Try different question phrasings
   - Test with various complexity levels
   - Explore different frameworks

### Known Limitations

- Maximum 3-4 frameworks per analysis (by design)
- Search quality depends on web_search tool availability
- Sequential Thinking requires MCP server
- Analysis length appropriate to complexity (not customizable per request)

---

## ✨ Tips for Power Users

1. **Request Specific Frameworks**
   "Use Porter's Five Forces to analyze..."

2. **Combine Frameworks Explicitly**
   "Apply SWOT and Cost-Benefit Analysis to..."

3. **Guide Search Strategy**
   "Research Chinese market specifically, then..."

4. **Expand Thinking Processes**
   Click on collapsed Sequential Thinking sections to learn

5. **Provide Feedback**
   "That framework choice worked well because..."
   "Next time, X framework would be better for..."

---

## 🎉 You're Ready!

Super Analyst 2.0 is now installed and ready to provide consulting-grade analytical insights.

**Try your first question:**
- Simple: "Explain design thinking to me"
- Medium: "Analyze OpenAI's competitive advantages"
- Complex: "Should we invest in quantum computing? Full assessment."

**Enjoy professional analytical capabilities at your fingertips!**

---

**Questions or Issues?** Refer to documentation in /references/ or check usage-examples.md for similar scenarios.

**Version:** 2.0 | **Status:** Production Ready | **Date:** October 26, 2025
