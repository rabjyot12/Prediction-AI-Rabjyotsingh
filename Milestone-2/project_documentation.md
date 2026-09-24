
# `project_documentation.md`


# Milestone 2 Project Documentation

## Prediction AI – Startup & Project Risk Analyzer

### Milestone 2: Risk Assessment, SWOT and Feasibility Analysis

---

## 1. Introduction

Milestone 2 extends the foundation created in Milestone 1 by evaluating the risks and feasibility of the submitted project.

The project information and market/competitor context from Milestone 1 are used to assess important risk factors and produce an overall project assessment.

---

## 2. Objective

The main objectives of Milestone 2 are:

1. Assess project-related risks.
2. Calculate an overall risk score.
3. Classify the project into a risk category.
4. Calculate success probability.
5. Generate a SWOT analysis.
6. Calculate project feasibility.
7. Provide structured outputs for Milestone 3.

---

## 3. Risk Assessment

The system evaluates five major factors:

- Market Competition
- Team Expertise
- Resource Availability
- Innovation Level
- Market Research

Each factor is evaluated using predefined rules and contributes to the overall risk score.

The resulting score represents the overall risk level of the project.

---

## 4. Risk Classification

The calculated risk score is converted into a risk status.


Risk Score >= 70
        ↓
HIGH RISK

Risk Score >= 40
        ↓
MEDIUM RISK

Risk Score < 40
        ↓
LOW RISK


## 5. Success Probability

The system calculates an estimated success probability from the overall risk score.

The formula used is:

Success Probability = max(0, 100 - Risk Score)

This provides a complementary measure to the risk score.

## 6. SWOT Analysis

The system generates a SWOT analysis containing four categories:

Strengths

Internal factors that can support the project.

Weaknesses

Internal limitations or areas that may negatively affect the project.

Opportunities

External opportunities that the project can potentially use.

Threats

External factors that may create challenges or risks.

The SWOT results provide additional context for understanding the project beyond the numerical risk score.

## 7. Feasibility Analysis

The system calculates a feasibility score using the relevant project assessment values.

The feasibility score provides an overall indication of how practical the project is based on the assessed factors.

The result is displayed along with the other Milestone 2 assessment outputs.

## 8. Application Workflow

The Milestone 2 workflow is:

Project Information
        ↓
Market & Competitor Information
        ↓
Risk Factor Assessment
        ↓
Overall Risk Score
        ↓
Risk Status
        ↓
Success Probability
        ↓
SWOT Analysis
        ↓
Feasibility Score
        ↓
Milestone 2 Assessment

## 9. Application Output

The application presents the assessment results to the user, including:

Risk Score
Risk Status
Success Probability
SWOT Analysis
Feasibility Score

These results provide a structured assessment of the project's current risk and feasibility.

## 10. Integration with Milestone 3

Milestone 2 acts as the input layer for the strategic reasoning functionality developed in Milestone 3.

The risk score, identified risks, SWOT analysis, feasibility score, project information, and market information are used to generate recommendations, mitigation strategies, and improvement suggestions.

The overall progression is:

Milestone 1
Project + Market Information
        ↓
Milestone 2
Risk + SWOT + Feasibility
        ↓
Milestone 3
Recommendations + Mitigation + Improvements
