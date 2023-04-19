# W-12785124 - Frozen Console after deleting a record

## Repro Steps
1. Clone repository and create a scratch org
2. Create 2 Accounts
3. Make sure that the record page in use is Left_Pinned_Account
4. Create a Lightning Console App
5. Open both Accounts
6. Open another browser window and delete one of the Accounts
7. Go back to the original browser and refresh the workspace tab that holds the deleted account
8. Observe an error in the tab
9. Switch to the other Account Tab
10. Switch back to the deleted Tab
11. Switch back to the other Account Tab

The screen will be blank now, and the job queue will be deadlocked.

