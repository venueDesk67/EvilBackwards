# LIFE OS67 — The Brain Tree

Mobile-first, local-first personal development RPG prototype.

## Run
Open `index.html` in a modern browser, or publish the folder using GitHub Pages. The service worker and installable web manifest require HTTPS (or localhost).

## Included
- Player profile and XP progression (100 XP per level)
- Seven positive-development attributes
- 67 catalogue positions; 15 historical specialisation records confirmed, 13 exact titles recovered in available history, 2 titles still unknown, and 52 additional slots reserved
- Three playable mission templates for every named specialisation and each core attribute
- Historical MIS-008–014 XP (515) imported once into player XP and reconciled against its audit ledger
- Interactive Life Map and Brain Tree navigation
- Evidence-required mission submission
- Goal and activity logging
- Knowledge archive and input terminal (local rule-based triage, not live AI)
- JSON backup and restore
- Responsive dark navy / purple / gold interface
- PWA manifest and basic offline app-shell cache

## Important limitations
- Browser storage is local to this device/browser; no cloud account or cross-device sync.
- The AI terminal is not connected to an external language model.
- Historical averages and skill levels are included only where recovered; unknown fields remain blank.
- Historical skill ratings are AI-assessed records, not independently verified competencies.
- The 52 unnamed catalogue positions are placeholders, not claimed recovered specialisation titles.
- Test on the target Android device before relying on it as the sole record keeper.

## Deploy with GitHub Pages
1. Upload all files in this folder to the repository root.
2. In GitHub, open Settings → Pages.
3. Select Deploy from a branch, choose `main` and `/ (root)`, then Save.
4. Wait for deployment to finish and open the published URL.
