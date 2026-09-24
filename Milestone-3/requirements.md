# Milestone 3 Requirements

## Project

**Prediction AI – Startup & Project Risk Analyzer**

## Milestone

**Milestone 3 – Recommendations & Strategic Reasoning**

---

## 1. Objective

The objective of Milestone 3 is to transform the risk assessment, SWOT analysis, feasibility results, project information, and market analysis from previous milestones into actionable strategic recommendations.

The system should identify what the project should do, why the action is important, how it addresses identified risks, and how the project can be improved.

---

## 2. AI Strategic Recommendation Engine

The system should generate:

- Overall Strategic Recommendation
- Risk-Based Recommendations
- Market Recommendations
- Technical Recommendations
- Financial Recommendations
- Operational Recommendations
- Improvement Suggestions
- Short-Term Action Plan
- Long-Term Action Plan

Each recommendation should be connected to the project's identified risks and assessment results.

---

## 3. Risk-Based Recommendations

For each important risk, the system should explain:

- The problem or risk
- Why the risk matters
- Recommended action
- How the action reduces the risk
- Priority of the recommendation

Recommendations should be prioritized where appropriate as:

- Critical
- High
- Medium

---

## 4. Risk Mitigation Engine

The system should generate mitigation strategies for major identified risks.

Each mitigation result should contain:

- Risk Name
- Category
- Description
- Impact
- Priority
- Recommended Mitigation Strategy
- Preventive Action
- Contingency Action

---

## 5. Improvement Engine

The system should generate practical improvement suggestions across:

- Product
- Market
- Technical
- Financial
- Operational
- Marketing

Each improvement should include:

- Improvement
- Reason
- Expected Benefit
- Priority

---

## 6. LangGraph Agent Workflow

The system should implement a structured agent workflow using six connected nodes:


analyze_project
      ↓
analyze_risks
      ↓
generate_recommendations
      ↓
generate_mitigation
      ↓
generate_improvements
      ↓
generate_final_response

## 7. LLM Integration

The system should support an LLM such as Google Gemini or OpenAI for strategic reasoning.

The API key should:

Be stored using an environment variable.
Never be hard-coded in the source code.

The system should also support a clearly labelled Demo Mode when an API key is not available.

## 8. Final Strategic Response

The system should combine the outputs of the different stages into a final response containing:

Project Summary
Risk Summary
Key Strategic Recommendations
Risk-Based Recommendations
Mitigation Strategies
Improvement Suggestions
Short-Term Action Plan
Long-Term Action Plan
Final Strategic Assessment

## 9. Dashboard

The application should provide sections for:

Project Information
Risk Assessment
SWOT
Feasibility
AI Recommendations
Risk Mitigation
Improvement Plan
Final Report

The M3 interface should allow the user to view the generated strategic outputs.

## 10. Data Storage

The system should store relevant project assessment and M3 results, including:

Project information
Risk information
Recommendations
Mitigation strategies
Improvements
Generated results
Timestamp
11. Acceptance Criteria

Milestone 3 should demonstrate that:

Previous milestone information is used.
Strategic recommendations are generated.
Recommendations are connected to identified risks.
Risk mitigation strategies are generated.
Improvement suggestions are generated.
The LangGraph workflow is represented using the required nodes.
The dashboard displays the M3 outputs.
Demo Mode works when an API key is unavailable.
The system can produce a final strategic response.
