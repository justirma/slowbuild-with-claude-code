Guide the user through the Feedback Analyzer tool.

## What this tool does
Takes customer feedback (support tickets, survey responses, Slack messages, etc.) and categorizes each item by type (bug, feature request, UX issue, praise) and priority (high, medium, low).

## Flow

1. Ask the user to paste their customer feedback. Multiple items separated by line breaks work best. If they don't have any handy, offer the sample data in `sample-data/sample-feedback.txt`.

2. Take their feedback and analyze it using this approach:
   - For each feedback item, determine:
     - **Category**: bug, feature_request, ux_issue, or praise
     - **Priority**: high, medium, or low (based on urgency, impact, sentiment)
     - **Reason**: one-line explanation for the priority
   - Produce a summary: total count, breakdown by category, breakdown by priority

3. Display the results clearly — grouped by priority (high first), with category tags.

4. Save the analysis to `my-work/feedback-analysis-[date].md`.

5. Ask: "Want to analyze another batch, or try the Pre-Read Generator? Run `/preread-generator` anytime."

## If "walk me through it" mode
Add these teaching moments (keep each to 1-2 sentences):
- **Before analysis**: "The categories — bug, feature request, UX issue, praise — cover the four types of feedback PMs deal with most. Clean buckets make prioritization faster."
- **After results**: "Notice the priority assignments. High = urgent or high-impact. This saves you from reading every ticket to find the fires."
- **After saving**: "You now have a snapshot you can drop into a sprint planning doc or share with eng. The analysis is the starting point, not the final word — always apply your judgment."
