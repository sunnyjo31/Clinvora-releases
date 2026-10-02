# HomeoClinic installers

This repository only holds the Windows installers of **HomeoClinic**, a clinic records app for homeopathy doctors. There is no source code here.

- Releases tagged `vX.Y.Z` are the versions clinics receive.
- Releases tagged `test-vX.Y.Z` (pre-releases) are for testing an update before it goes to clinics.

The app updates itself: it installs a release only when the update notice it reads is signed with the developer's key and the downloaded file's SHA-256 matches. Downloading an installer from here by hand is fine too; it needs Windows 7 SP1 or later and .NET Framework 4.8.
