CUET PG GEOPHYSICS V9 — LEARNING / CHAPTER UPDATE

What changed:
1. Chapters are now question-only testing sessions. No explanations appear between questions. A full answer review with explanations appears after the session.
2. Practice is now a Concept & Equation Lab instead of a sudden MCQ feed.
3. Equation cards are the primary learning deck.
4. Concept cards are separate; Mixed Recall combines both.
5. Cards use reveal -> self-rating -> spaced return scheduling.
6. The user can learn 20-card decks at a time instead of being dropped directly into questions.
7. Mistake practice remains separate from normal chapter sessions.
8. Existing 1,000-question questions.json is retained.
9. Existing chapter_sessions.json is retained.
10. New learning_cards.json contains the equation/concept learning deck.

GitHub update:
Replace/add these files in the existing repository:
index.html
learning_cards.json
chapter_sessions.json
questions.json
manifest.json
sw.js
icon.svg

The service-worker cache is V9 so the installed PWA can refresh its assets.
