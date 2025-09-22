# The Science of the Unknown Universe — Hidden Chamber

This repository hosts the **SOYUU Codex** and its audio archive.

## 🔑 Access
- Open [the GitHub Pages site](https://YOURNAME.github.io/soyuu-chamber/)
- www.unknownuniverse.org
- https://agwilkins.github.io/SOYUU 
- A **password gate** will appear.  
- The secret word is defined in `index.html` under:
  ```js
  const correct = "flame"; // <-- change me
  Change this phrase to anything you like and commit the update.
  index.html         → the Codex + audio players
audio/             → all .m4a recordings
   01 Accept 1 Strategy.m4a
   02 Accept 2 Thought.m4a
   ...
   68 Introduction to Ascend.m4a
Each Threshold / Plate / Scroll / Fragment / Gate in the Codex has its own <audio> player, wired directly to the file in audio/.
🎧 Adding / Updating Audio

Navigate to the audio/ folder in this repo.

Click Add file → Upload files.

Drag in your new or updated .m4a recordings.

Ensure the filenames match exactly what index.html expects (see soyuu_expected_filenames.txt).

Example: 01 Accept 1 Strategy.m4a

Spaces and capitalization matter!

Commit changes.

💡 If GitHub won’t let you upload into a new folder, add a dummy file (like audio/.gitkeep) first. This forces Git to recognize the folder.
🌐 Going Live (GitHub Pages)

Go to Settings → Pages.

Under Build and deployment:

Source: Deploy from branch

Branch: main

Folder: / (root)

Save.

Your chamber will appear at:
https://YOURNAME.github.io/soyuu-chamber/
🛠️ Troubleshooting

Audio won’t play?

Check if the file opens directly:

https://YOURNAME.github.io/soyuu-chamber/audio/01%20Accept%201%20Strategy.m4a


If that 404s, the file is missing or misnamed.

Upload button missing?

Create your first file (e.g. a dummy index.html) → commit → the “Add file” menu appears.

Wrong extension case?

Make sure files end with .m4a (not .M4A).

🕯️ Notes

This chamber is invite-only. Share the URL and password only with those you trust.

The Codex text is woven directly into index.html. To edit or extend it, open the file and commit changes.

The password gate is simple front-end code. Don’t use it for high-security secrets. It’s a ritual veil, not a vault.

---

Would you like me to also generate the `soyuu_expected_filenames.txt` directly into the repo (next to `index.html`) so anyone can always check “what audio is expected”?
