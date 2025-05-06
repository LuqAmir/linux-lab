# Phase 3: Permissions and Shared Access — "Team Web Project"

## Tasks:
- [x] Create a shared web directory at `/var/www/clientsite`
- [x] Create two users: `client1`, `client2`
- [x] Create a group `webdevs`
- [x] Add both users to `webdevs` group
- [x] Set `/var/www/clientsite` to be owned by `root:webdevs`
- [x] Set permissions to allow group read/write/execute access (770)
- [x] Enable sticky group bit (`chmod g+s`) to ensure inherited group ownership
- [x] Switch to `client1` and `client2` to test file creation and access
