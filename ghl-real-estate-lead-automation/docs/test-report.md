# End-to-end test report

## Scope

The workflow was tested with an existing dummy contact. No customer-facing email, SMS, or WhatsApp action was included.

## First test

The opportunity, assignment, and tagging actions executed successfully. The internal notification was skipped because it ran before the contact had an assigned owner.

Observed reason:

`Notification for assigned user: No user assigned for the contact`

## Correction

The internal notification was moved after the assignment action. The workflow was saved and tested again with the same dummy contact.

## Final test

| Execution order | Action | Status |
|---:|---|---|
| 1 | Add to workflow | Added |
| 2 | Create or update opportunity | Executed |
| 3 | Assign lead owner | Executed |
| 4 | Internal appointment notification | Executed |
| 5 | Add appointment tag | Executed |
| 6 | End of workflow | Finished |

## Outcome

The corrected workflow completed end-to-end and was published only after the successful second test.

