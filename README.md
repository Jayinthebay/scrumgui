scrumgui
========

A Scrum Board for GitLab

![Alt text](http://oi60.tinypic.com/rrhwyg.jpg "The ScrumGUI interface to GitLab")

# Features: #

- Touch / Drag drop scrum board interface!
- Gitlab issues = ScrumGUI Tasks 
- Uses concept of "feature branch" workflow
- ScumGUI Task types: FEATURE (Green), ENHANCEMENT (Blue), BUG (Red), OTHER (Gray)
- When moving ScrumGUI Task to "For Review" status, you are asked which recent commit to link to (or N/A)
- ScrumGUI then automatically creates & processes Merge Request based on Approve/Deny (Yes, it's awesome.)
- If approved, issue is merged the "DEV" branch. You can then Merge DEV -> MASTER when you desire.
- Scrumboard user roles mapped to Gitlab Roles (e.g. guest, reporter, developer..)
- Indication of new Issue comments and Git releated activity on each ScrumGui Task
- 
