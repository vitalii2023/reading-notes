# Read 03 reading Notes - Revisions and the Cloud

**What is Git?**
Git is a DVCS that stores data in a file system made up of snapshots. 

Snapshots
Git creates a snapshot of the file and stores a reference to it.

Local operations
Git mostly relies on local operations because most necessary information can be found in local resources. This allows for process expediency because a project’s history resides on the local disk, eliminating the need to fetch history information from the server, and allowing one to continue work on a project even when not online or on a VPN.

Tracking changes
Every change applied to any file or directory is tracked by Git. And, as the gatekeeper, Git will always detect file corruption or loss of information in transit.

Loss of data
Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. Git makes it extremely difficult for a snapshot of your file that is committed to be lost.

States:

Committed
Data is securely stored in a local database

Modified
File has been changed but not committed to the database

Staged
Flagged a file’s changed version to be committed in the next snapshot