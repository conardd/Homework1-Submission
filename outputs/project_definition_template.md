
# PROJECT DEFINITION TEMPLATE

## 1. PROJECT TITLE
[Give your project a name]

Example: "Multi-Paper Methodology Comparison Tool"

## 2. THE PROBLEM
What research problem are you solving?

[Be specific! What's painful in your current workflow?]

Example: "I need to compare how different papers approach sentiment 
analysis, but manually reading 20 papers and extracting their methods 
takes days."

## 3. YOUR SOLUTION
How will your agent solve this problem?

[Describe the agent's behavior at a high level]

Example: "My agent will: (1) search for papers on a topic, (2) extract 
methodology sections, (3) identify key techniques, (4) create a 
comparison table, (5) highlight novel approaches."

## 4. USER WORKFLOW
How will someone use your agent?

[Describe the user interaction]

Example:
- User inputs: Research topic, number of papers to analyze
- Agent does: Search, extract, analyze, compare
- User receives: Comparison table + insights document

## 5. COMPONENTS
Which techniques from the course will you use?

[Check all that apply, explain how]

☐ CO-STAR prompting - [How will you use it?]
☐ Structured outputs (JSON/XML) - [How will you use it?]
☐ Chain-of-thought - [How will you use it?]
☐ Model selection - [Which models for which tasks?]
☐ MCP/Tool use - [Which tools?]
☐ Multi-step workflow - [Describe the flow]
☐ Other: [What else?]

## 6. SUCCESS CRITERIA
How will you know if your project succeeded?

[Define measurable success]

Example:
- Functional: Correctly extracts methods from 80%+ of papers
- Useful: Saves me at least 4 hours on my next literature review
- Quality: Comparison table is accurate and readable
- Demo-able: Can show end-to-end workflow in 5 minutes

## 7. SCOPE
What's IN scope and OUT of scope?

IN SCOPE (Must have):
- [Feature 1]
- [Feature 2]
- [Feature 3]

OUT OF SCOPE (Nice to have, but not now):
- [Feature that would be cool but not essential]
- [Feature you might add later]

## 8. DATA SOURCES
What data will your agent work with?

[Where does the data come from?]

Example: arXiv papers (via search API), user-uploaded PDFs, etc.

## 9. TECH STACK
What tools/libraries will you use?

[List the technical components]

Example:
- LLM: Claude Sonnet (API) or Llama 3.1 (local)
- Tools: arXiv API, PyPDF for parsing, pandas for tables
- MCP: brave-search server, filesystem server
- Output: Markdown reports, CSV tables

## 10. TIMELINE
What's your week-by-week plan?

Week 1 (This week):
  - [Task 1]
  - [Task 2]

Week 2-3:
  - [Task 3]
  - [Task 4]

Week 4 (Project Insight I):
  - Demo: [What will you show?]
  - Get feedback

Week 5-6:
  - [Refinements based on feedback]

Week 7 (Project Insight II):
  - Finalize scope

Week 8-10:
  - [Final implementation]
  - [Testing]
  - [Documentation]

Week 10 (Final Presentation):
  - Demo complete agent

## 11. RISKS & MITIGATION
What could go wrong?

Risk 1: [What could go wrong?]
  Mitigation: [How will you handle it?]

Risk 2: [What could go wrong?]
  Mitigation: [How will you handle it?]

Example:
Risk: API rate limits on paper searches
  Mitigation: Implement caching, use local models as fallback

## 12. STRETCH GOALS
What would you add if you had more time?

[Nice-to-have features]

Example:
- Web UI instead of notebook
- Support for more paper sources
- Automated quality checks
- Export to LaTeX
