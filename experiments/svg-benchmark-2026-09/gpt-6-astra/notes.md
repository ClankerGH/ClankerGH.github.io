## Output behavior

- The v2 prompt successfully caused the model to create `observatory-original.svg`.
- However, instead of surfacing the file as a downloadable attachment, the model returned only its internal sandbox path:
  `/mnt/data/observatory-original.svg`
- A follow-up transport-only instruction was required to expose the already-created file to the user.
- No regeneration, repair, redesign, or optimization was requested.
