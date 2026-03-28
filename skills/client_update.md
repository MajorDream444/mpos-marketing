# Skill: Client Update

## Purpose
Log and update client or lead records across systems when status changes.

## Trigger Command
```
UPDATE_CLIENT
Name: [name]
Status: [new status]
Notes: [what happened]
Campaign: [which campaign]
```

## Inputs
- Client / lead name
- New status
- Action taken
- Campaign name
- Date

## Process
1. Locate existing record (Obsidian file or tracking sheet)
2. Update status field
3. Add timestamped note
4. Flag if escalation is needed
5. Confirm update complete

## Outputs
- Confirmation of update
- Updated record summary
- Escalation flag (if status = Hot Lead, Application Submitted, or Deal Closed)

## Status Options
- Prospect — identified, not yet contacted
- Contacted — first message sent
- Engaged — replied, conversation active
- Qualified — Green status confirmed
- Application Sent — link delivered
- Application Submitted — form completed
- Call Booked — call scheduled
- Call Completed — call done, decision pending
- Closed Won — sale confirmed
- Closed Lost — not a fit
- Nurture — Yellow, follow-up sequence active

## Rules
- Every status change must be logged
- Never let a Green lead go 24 hours without a log entry
- Closed Lost leads get a note on why — use for future ICP refinement

## Success Metric
- Logging accuracy
- Time between status change and update entry
