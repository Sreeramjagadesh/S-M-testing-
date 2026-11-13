# S&M testing

Test repository for the support ticket automation.

- Name each branch after its ClickUp ticket: `CU-<ticket id>-short-description`. That is how the automation links a pull request to a ticket.
- The CI check fails while a file named `FAIL` exists in the branch, so a demo can show a failed check on demand.
- A pull request needs approval from someone other than its author before the ticket can move on.
