### Steps to change role via Keycloak



1. Log in to Keycloak.
2. Go to "Users" on the left pane.
3. Select your user profile. 
4. Navigate to the "Role mapping" tab (top-center-left of the page).
5. Here, you should see all your assigned roles.
6. To unassign roles, select them and click "Unassign" on the top-center.
7. To assign roles, click on the "Assign role" button.
8. It should open a popup with different roles; however, it may not be showing the roles you are looking for be default.
9. Click on "Filter by clients" on the top left of the popup.
10. Change it to "Filter by realm roles."
11. Now, you should see all the supervisor and manager roles from different factories.
12. NOTE: It only displays 10 roles by default per page (at least on my screen); to find the role you are looking for, you may have to go to next pages of roles (thought I would mention it since it may be easy to miss :]).
13. Select the roles you want to add to your profile (I usually just keep one role at a time), and click the "Assign" button on the bottom left of the popup.
14. Navigate to the frontend (local or test). 
15. Open Dev-Tools in your browser.
16. Go to your `Session Storage` (lives in the `Application` tab in Chrome).
17. Delete you the `jwt` stored in it, so that login is triggered again upon refresh.
18. Refresh the page.
19. That's it :). You shouls see your role updated.



Hope that was easy to follow. Thank you.
#### Note: if something was unclear, please download and see the [accompanying video](https://github.com/AhmadAtMunters/Onboarding-Ticket-Suggestions-for-improvements./blob/main/keycloak-role-changes/Changinng%20Roles.zip).




