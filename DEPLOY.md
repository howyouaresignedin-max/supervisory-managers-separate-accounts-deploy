# Step-by-Step Deploy Checklist

## For each of the 7 Supervisory Managers

1. **Create the Grok account**
   - Go to https://grok.x.ai or the Grok app
   - Sign up with a dedicated email (corporate or new Gmail alias)
   - Complete any verification steps

2. **Connect the required services** (inside the new Grok account)
   - Automations (required)
   - Gmail
   - Google Drive
   - Google Calendar
   - GitHub
   - Finance (optional but recommended)

3. **Create the automation**
   - Open a new chat in that account
   - Paste the full JSON from the matching file in `configs/`
   - Say:  
     `Create a new automation with this exact configuration:`  
     then paste the JSON

4. **Verify**
   - Confirm the automation appears in the Automations list
   - Optionally run it once with `automation_run_now` to test

5. **Repeat** for the remaining 6 accounts

## Timezone
All schedules use `America/Los_Angeles` (Pacific Time).

## Notification
Default = email + app notification.

## After all 7 are live
You can optionally pause or delete the old automations on the original account if they are no longer needed.
