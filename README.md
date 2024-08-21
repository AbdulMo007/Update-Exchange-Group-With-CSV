# Update-Exchange-Group-With-CSV
How the script works:
Prompt for Group Name: The script asks for the group name and checks for similar group names.
Display and Confirm: If multiple groups are found, it displays them with their identities and asks you to confirm the correct one.
Check Membership: For each user in the CSV, the script checks if they are in the group or any sub-group. If not, it adds them.
Identify Non-CSV Members: It compares the current members with the CSV entries and identifies those in the group but not in the CSV.
Prompt for Removal: The script asks if you want to remove users who are in the group/sub-groups but not in the CSV. If confirmed, it removes them.
Cleanup: Finally, the session with Exchange Online is closed.
This script makes the process more dynamic and interactive, ensuring you have control over the group operations.
