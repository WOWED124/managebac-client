# managebac-client

A Mac app for your ManageBac assignments, grades and notifications.
Needs macOS 15 or newer (Apple silicon or Intel).

INSTALL
1. Drag "ManageBac Client" into your Applications folder.
2. The first time you open it, macOS will say it can't check the app for
   malware (it isn't from the App Store). That's expected. Do ONE of these:
   - Open System Settings > Privacy & Security, scroll down, and click
     "Open Anyway" next to ManageBac Client, then confirm.
   - Or, in Terminal:  xattr -dr com.apple.quarantine "/Applications/ManageBac Client.app"
3. Open the app, type your school's ManageBac address (like
   yourschool.managebac.com) and choose "Continue with School Account".
   Sign in on your school's normal page (Google, Microsoft or ManageBac).
   There's also "Explore with Demo Data" to look around without signing in.

YOUR DATA
- Everything is stored on YOUR Mac only, outside the app: your saved sign-in
  in your Keychain, and your cached assignments/grades in the app's private
  folder (~/Library/Containers/com.crowndancer.ManageBacClient).
- The app never sees or stores your password.
- Nothing is sent anywhere except to your school's ManageBac and Faria's
  notification service (the same ones the ManageBac website uses).
- To start over: Settings > Account > Sign Out. To remove the app completely,
  also delete the app and the folder above.

NOTES
- The Grades tab averages assessments (60%) and classwork (40%), using
  ManageBac's category names ("Sumativo/Summative/Assessment" and
  "Formativo/Formative/Tasks"). Schools that grade differently may see
  different results.
- This is an unofficial app, not made or endorsed by ManageBac.
