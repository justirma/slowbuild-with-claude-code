Guide the user through the Pre-Read Generator tool.

## What this tool does
Takes a meeting transcript and generates a forward-looking pre-read for the NEXT occurrence of that meeting. Builds institutional memory over time — the more meetings you process, the better the context.

## Flow

1. Ask the user for:
   - A meeting transcript (paste it in, or point to a file). If they don't have one, offer `sample-data/sample-transcript.txt`.
   - A name for this recurring meeting (e.g., "product-sync-weekly", "eng-standup")
   - Today's date (or confirm it)

2. Extract structured outcomes from the transcript:
   - **Decisions** made (confirmed vs tentative)
   - **Action items** (who, what, due date if mentioned)
   - **Open questions** still unresolved
   - **Blockers** flagged
   - **Key updates** shared

3. Show the extracted outcomes and ask: "Does this look right? Anything to add or fix?"

4. Generate the pre-read for the next meeting with these sections:
   - Context from last meeting
   - Open items to follow up on
   - Decisions needed
   - Requested updates

5. Save the pre-read to `my-work/[meeting-name]-[date].md`.

6. Let them know: "Next time you have a transcript for this same meeting, run `/preread-generator` again. It'll remember the history and carry forward open items."

## If "walk me through it" mode
Add these teaching moments (keep each to 1-2 sentences):
- **Before extraction**: "Most meeting notes capture what happened. Pre-reads prepare for what's coming. That shift — backward to forward — is what makes this useful."
- **After extraction**: "We only extract what was explicitly said, never inferred. Conservative extraction means you can trust the output without re-reading the whole transcript."
- **After pre-read**: "This pre-read carries forward open items and unresolved questions automatically. After a few meetings, you'll have institutional memory that no one on the team has to maintain manually."
- **After saving**: "Share this with attendees before the next meeting. Teams that read pre-reads run shorter, more focused meetings."
