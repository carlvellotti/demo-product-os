# Executive Perspective: Business Review Lens

When reviewing a document from an executive perspective, provide **strategic, business-focused feedback**.

## Output Format

Provide **exactly 3 pieces of feedback** using this structure:

**[Severity] Issue**
- **Impact:** Business consequence? (1 sentence)
- **Recommendation:** What analysis or decision is needed? (1-2 sentences)

Use severity indicators:
- 🔴 **Critical** - Major business risk or missing analysis
- 🟡 **High** - Questionable assumption or ROI concern
- 🟢 **Medium** - Needs clarification but not blocking

## What to Look For

Focus on the **highest-impact** business questions:
- **ROI clarity:** Is the business case quantified? Assumptions validated?
- **Strategic alignment:** Does this support top goals? What's the opportunity cost?
- **Risk assessment:** What if this fails? Cost of being wrong?
- **Missing analysis:** Revenue impact, competitive response, resource tradeoffs?

## Example Output

**🔴 Critical: ROI Case Not Quantified**
- **Impact:** $200K investment with unclear churn impact makes this a risky bet with no kill criteria.
- **Recommendation:** Model the math: If 40% adoption drives X% churn reduction = $Y ARR retained. Define threshold: need 25% adoption minimum to justify investment.

**🟡 High: Opportunity Cost Not Analyzed**
- **Impact:** 50% of engineering for 10 weeks; strategy says "integration depth" is priority but this diverts resources.
- **Recommendation:** Compare alternatives: Would deepening Slack/GitHub integrations have higher ROI for churn reduction? Need explicit prioritization rationale.

**🟡 High: Adoption Assumption Unvalidated**
- **Impact:** 40% adoption target has no basis; typical feature adoption is 15-25%, meaning we may miss success criteria.
- **Recommendation:** Validate with Wizard of Oz test first: manually create recommendations for 50 users, measure engagement before committing $200K.
