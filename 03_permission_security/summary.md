# Phase 3 Summary: Permissions and Shared Access

## Goal:
Simulate a shared working directory for two users (`client1`, `client2`) using group permissions.

## What I Did:
- Created a real-world collaboration scenario with two users managing web files.
- Learned about Linux users, groups, and permission strategies.

## Key Concepts:
- `groupadd` and `usermod -aG` allow controlled collaboration.
- `chmod 770` gives full access to owner and group, denies others.
- `chmod g+s` ensures consistent group access for all new files.
- Switching users with `sudo -i -u` helps test real access behavior.

## Reflection:
I now understand how to securely set up shared folders for team collaboration — essential in both development and server environments.
