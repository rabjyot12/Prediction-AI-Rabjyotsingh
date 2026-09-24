# Milestone 2 Requirements

## Project

**Prediction AI – Startup & Project Risk Analyzer**

## Milestone

**Milestone 2 – Risk Assessment, SWOT Analysis and Feasibility Analysis**

---

## 1. Objective

The objective of Milestone 2 is to use the project, market, and competitor information collected in Milestone 1 to evaluate the potential risks and feasibility of the project.

The system should calculate an overall risk score, classify the risk level, estimate success probability, generate a SWOT analysis, and calculate a feasibility score.

---

## 2. Risk Assessment

The system should evaluate the project using the following risk factors:

- Market Competition
- Team Expertise
- Resource Availability
- Innovation Level
- Market Research

Each factor should contribute to the overall risk score using predefined scoring rules.

---

## 3. Risk Score

The system should calculate an overall risk score based on the identified risk factors.

The risk score should be used to determine the overall risk status of the project.

### Risk Status

- **70 or above:** High Risk
- **40–69:** Medium Risk
- **Below 40:** Low Risk

---

## 4. Success Probability

The system should calculate the estimated success probability from the overall risk score.

The calculation should follow:

```text
Success Probability = max(0, 100 - Risk Score)
```

A higher risk score therefore results in a lower estimated success probability.

## 5. SWOT Analysis

The system should generate a SWOT analysis containing:

Strengths
Weaknesses
Opportunities
Threats

The SWOT analysis should be based on the project information and assessment results.

## 6. Feasibility Analysis

The system should calculate an overall feasibility score using the relevant project assessment factors.

The feasibility result should help determine how practical and viable the project is based on the available information.

## 7. User Interface

The application should allow users to:

Enter or review project information.
Provide values for the risk assessment factors.
View the overall risk score.
View the risk status.
View success probability.
View SWOT analysis.
View feasibility results.

## 8. Data Flow

The Milestone 2 workflow should follow:

```text
Milestone 1 Output
       ↓
Risk Factor Assessment
       ↓
Risk Score
       ↓
Risk Status
       ↓
Success Probability
       ↓
SWOT Analysis
       ↓
Feasibility Analysis
       ↓
Milestone 2 Results
```

## 9. Expected Output

At the end of Milestone 2, the system should provide:

Overall risk score
Risk classification
Success probability
SWOT analysis
Feasibility score
Structured assessment results for use in Milestone 3

## 10. Integration with Milestone 3

The outputs from Milestone 2 should be used by Milestone 3 to generate:

Strategic recommendations
Risk mitigation strategies
Improvement suggestions
Strategic action plans
