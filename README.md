# Shortlisted_App
Swiping app with SSA data to choose baby names


Here’s both, written separately so you can use them independently.

README.md (for GitHub)

Shortlisted

A browser-based baby name swipe app built on official SSA 2025 data. No accounts, no ads, no installs. Just open the file and start swiping.

Built by u/Double_Ostrich_13

What it does

	•	Swipe or click through every name in the 2025 SSA dataset (17,297 female · 13,930 male)
	•	See each name’s 2025 rank and how many babies were given that name
	•	Keep, pass, skip, or undo — no commitment, go at your own pace
	•	Filter by gender, starting letter, top N by popularity, or sort order
	•	View and manage your Kept and Passed lists at any time
	•	Move names between lists if you change your mind
	•	Copy your kept list or export it as a CSV

Works on desktop and mobile. No internet connection required after the file loads.

How to use it

Desktop

	1.	Download shortlisted.html
	2.	Open it in any browser (Chrome, Firefox, Safari, Edge all work)
	3.	That’s it — start swiping

Arrow keys work on desktop:

	•	→ Keep
	•	← Pass
	•	↑ Skip (come back to it later)
	•	↓ Undo last swipe

Mobile

	1.	Download the file to your phone, or open it from a sharing link
	2.	Open it in your browser
	3.	Swipe the card left to pass, right to keep
	4.	Tap the ♥ Lists button to see your kept and passed names

Saving your progress

Your progress saves automatically in your browser’s local storage. This means:

	•	✓ Closing the tab and coming back works fine
	•	✓ Closing the browser entirely works fine
	•	✓ Restarting your computer works fine
	•	✗ Clearing your browser cache/history will reset progress
	•	✗ Private / incognito mode does not save progress
	•	✗ Switching browsers loses progress (Chrome save ≠ Firefox save)
	•	✗ Switching devices loses progress

Always use the same browser on the same device.

Data source

All name data is from the U.S. Social Security Administration 2025 dataset. Only names given to 5 or more babies are included, which is SSA’s standard reporting threshold.

Technical notes

Single self-contained HTML file. No frameworks, no dependencies, no external calls after the Google Fonts load. All name data is embedded directly in the file. localStorage is used for persistence — nothing is sent anywhere.

File size is ~978KB due to the embedded name data.
