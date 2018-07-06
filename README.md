# move-team
Used to consolidate teams by copying one team's members, owners, channels, and files to another team.

# DISCLAIMER
###############Disclaimer##################################################### THIS CODE IS PROVIDED AS IS WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT. ###############Disclaimer#####################################################

# OPTIONS
What this script does: 
1. Establish connection to Microsoft Teams and Azure Active Directory in the user's context.
2. Prompt user for source and target teams.
3. Read and report source and target team membership, compare and prompt whether or not to add members missing from target team.
	If current user is owner in target team, add members/owners to target team. 
4. Loop through source channels and either confirm they exist in the target team or create them.
5. Copy the files from each source channel into the corresponding target channel.

# EXAMPLE
#Run the script with no switches. Menus and prompts are presented at run time.
.\move-teams.ps1
