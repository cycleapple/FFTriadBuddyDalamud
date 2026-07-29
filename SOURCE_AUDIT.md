# API13 / Taiwan 7.3 source audit

- Upstream: `MgAl2O4/FFTriadBuddyDalamud`
- Selected upstream commit: `acb68f2db8037b797a6254a0c4a8d1fbe1dce376`
- Commit date: `2025-08-11T03:27:21Z`
- Parent API migration commit: `069423d8c0e119507d239312775d0afbf6bb4f91`
- Parent commit date: `2025-08-10T17:05:20Z`
- Embedded `triad-shared` commit: `85c2c4476a30f316bfb1ba5c0343cba5b584e371`
- Audited compatibility window: 2025-08-05 through 2025-12-16
- Target environment: FFXIV Taiwan 7.3 and Dalamud API13

The selected commit is inside the requested compatibility window. Its parent
explicitly migrates the plugin to API13 / game 7.3, and the selected follow-up
removes obsolete percent replacement in accordance with the Dalamud v13
migration notes. Later upstream commits are intentionally excluded from this
compatibility build.
