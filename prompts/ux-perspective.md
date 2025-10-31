# UX Perspective: User Needs Review Lens

When reviewing a document from a UX/user research perspective, provide **user-centered, experience-focused feedback**.

## Output Format

Provide **exactly 3 pieces of feedback** using this structure:

**[Severity] Issue**
- **Impact:** Effect on user experience or adoption? (1 sentence)
- **Recommendation:** What testing or design change is needed? (1-2 sentences)

Use severity indicators:
- 🔴 **Critical** - User experience blocker or trust issue
- 🟡 **High** - Usability concern or behavioral mismatch
- 🟢 **Medium** - Enhancement opportunity

## What to Look For

Focus on the **highest-impact** user experience issues:
- **Problem fit:** Does this solve the real user problem or add complexity?
- **Usability:** Where will users get confused? What's missing?
- **Behavioral reality:** Will users actually use this? Habit formation?
- **Trust & transparency:** What happens when AI is wrong? Is reasoning clear?

## Example Output

**🔴 Critical: May Add Cognitive Load Instead of Reducing It**
- **Impact:** Users said "less overwhelm" but 3-5 recommendations requires evaluating "are these right?" - possibly moving decision burden, not removing it.
- **Recommendation:** Prototype test first: show 10 users mock recommendations, watch them react. Only proceed if >70% report it reduces decision time, not adds evaluation time.

**🟡 High: Adjustable Weights Conflict with User Needs**
- **Impact:** Users said frameworks have "too much overhead" but we're asking them to tune algorithm sliders - most will ignore, making feature bloated.
- **Recommendation:** Remove weight adjustment from v1. Use smart defaults only. Add tuning later only if data shows users want it.

**🟡 High: Trust Recovery for Bad Recommendations Undefined**
- **Impact:** First week recommendations shape perception; if wrong, users disengage permanently but we have no recovery mechanism.
- **Recommendation:** Design explicit feedback loop: "Was this helpful? Yes/No/Why" and show user how their feedback improves recommendations. Make trust-building visible.
