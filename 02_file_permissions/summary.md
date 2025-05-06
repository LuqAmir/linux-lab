# Phase 2 Summary: Hosting Simulation — File Permissions & Ownership

## Task 1: Folder Structure
- Created `hostpro/` with subfolders:
  - `clients/` containing `client1/` and `client2/`
  - `backups/` and `logs/` for private storage
- Simulates a real web hosting structure.

## Task 2: HTML Files for Clients
- Used `echo` to write a simple homepage (`index.html`) for each client.
- This mimics placing web files inside a client's public directory.

## Task 3: Ownership
- Used `sudo chown -R $USER:$USER` to ensure you own all files and folders.
- Prevents permission issues when modifying or accessing files.

## Task 4: Permissions
- `chmod -R 755` for `clients/`: allows public read but restricts write.
- `chmod -R 700` for `backups/` and `logs/`: only you can access.
- This separation simulates real security practices in hosting.

## Task 5: Verification
- Used `ls -lR` to recursively list all files and permissions.
- Ensures everything is structured and secured correctly.


