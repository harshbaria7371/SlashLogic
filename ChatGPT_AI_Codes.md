# ChatGPT Prompt Command Library

## Overview
This document lists reusable pseudo-commands (prompt patterns) to structure ChatGPT responses effectively. These are not native commands but prompt engineering techniques.

---

## 1. Analysis & Strategy Frameworks
- /swot → Strengths, Weaknesses, Opportunities, Threats  
- /ooda → Observe, Orient, Decide, Act  
- /pestle → Political, Economic, Social, Technological, Legal, Environmental  
- /5forces → Porter’s Five Forces  
- /rootcause → Root cause analysis (5 Whys)  
- /gap → Gap analysis  
- /risk → Risk identification + mitigation  
- /tradeoff → Pros vs cons  

---

## 2. Problem Solving & Thinking Modes
- /stepbystep → Forces structured reasoning
- /firstprinciples → Break problem to fundamentals
- /decisiontree → Explore all possible paths
- /debug → Identify issue + fix (great for code/testing)
- /optimize → Improve efficiency/performance
- /simplify → Reduce complexity
- /compare → Side-by-side comparison

---

## 3. Coding & QA
- /testcases → Generate test cases (with edge cases)
- /bdd → Convert to Given/When/Then
- /automation → Convert manual test → automation steps
- /framework → Suggest automation framework structure
- /locator → Generate XPath/CSS
- /mockdata → Generate test data
- /assertions → Suggest validations
- /api-test → API test scenarios
- /performance → Performance testing scenarios
- /security-test → Security test cases

---

## 4. Writing & Content Generation
- /rewrite → Improve text
- /summarize → Short summary
- /expand → Add detail
- /tone → Change tone (formal, casual, etc.)
- /email → Draft email
- /doc → Structured documentation
- /blog → Blog-style writing
- /bullet → Convert to bullet points

---

## 5. Learning & Explanation Modes
- /eli5 → Explain like I’m 5
- /deepdive → Detailed explanation
- /examples → Provide examples
- /analogy → Explain with analogy
- /quiz → Generate questions
- /cheatsheet → Quick reference

---

## 6. Productivity & Planning
- /plan → Step-by-step plan
- /roadmap → Long-term roadmap
- /timeline → Time-based breakdown
- /checklist → Action checklist
- /prioritize → Rank tasks
- /okr → Objectives & Key Results

---

## 7. Creativity & Ideation
- /brainstorm → Generate ideas
- /ideas → Variations of concepts
- /name → Naming suggestions
- /pitch → Startup/product pitch
- /story → Story generation
- /twist → Creative variations

---

## 8. Data & Structure Transformation
- /table → Convert to table
- /json → Convert to JSON
- /csv → Convert to CSV
- /schema → Generate schema
- /format → Clean formatting

---

## 9. Role-Based Commands
- /actas tester
- /actas architect
- /actas productmanager
- /actas devops
- /actas interviewer

---

## 10. Advanced Hybrid Commands
- /swot + /plan → Strategy + execution
- /debug + /optimize → Fix + improve
- /testcases + /bdd + /automation → Full QA pipeline
- /compare + /decisiontree → Better decisions

---

## Usage Template

```
/command
Context:
<your problem>

Output format:
<expected result>
```

### Example

```
/testcases
Context: Login API with JWT auth
Output: Table with Positive, Negative, Edge cases
```

---

## Notes
- These are prompt engineering techniques, not built-in commands.
- Combine commands for better results.
- Customize commands for your workflow (e.g., /qa-master).
