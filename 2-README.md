# Recall

A private, standalone flashcard study app. No accounts, trackers, dependencies, or build step.

## Open

Download this repository (Code > Download ZIP), unzip it, and open `index.html` in a browser. For a local web server, run `python3 -m http.server 8000` in this folder and open the address shown by Python.

## Study

1. Select the APUSH Unit 3 set, or choose Import to add your own.
2. Paste one card per line with a literal tab between the term and definition. The included `APUSH_Quizlet_Study_Guide.txt` uses this format.
3. Tap a flashcard to flip it; use the arrows to move. Shuffle or change the starting side if you want.
4. In Learn mode, type an answer, reveal the correct answer, then choose Got it or Study again. This is self-grading, not automatic correctness checking.
5. Export any set as a tab-separated `.txt` backup.

Sets and progress stay in this browser on this device. They do not sync between devices. Clearing browser data can remove them. When storage is unavailable, the app keeps working for the current session and shows a notice. Export backups before clearing data.

## Privacy

Card text is only stored locally. The app makes no network requests. This repository is intended to stay private. Do not enable a public static deployment unless you intend to make its bundled APUSH set visible to others.

## Source

Generated with Claude for Geo, then reviewed and tested. The APUSH set is the supplied 223-card study guide. No Quizlet code, logos, or assets are included.
