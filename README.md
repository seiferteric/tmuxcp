# tmuxcp
Script to copy files from tmux session to your local machine. This can be useful if you are ssh'ing several hosts deep and don't have direct access to SCP a file over.

## Usage
Start a tmux session on your local machine, ssh to remote host. In another terminal run: tmux <src> <dst> and wait for it to finish! Best to verify it was correctly copied with your favorite checksum.
