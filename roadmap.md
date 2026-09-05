# Roadmap

- [x] Clone storyweaver-sync-aid into this project, store API keys as secrets
- [x] Remove dark/mysterious tone from prompts, style, sanitizer and video grades
- [x] Webtoon/manhwa page style, high-detail prompts, max render quality (8 steps, 1344x768)
- [x] Verify end-to-end (bible → brief → prompts → image) — 3/3 panels generated in browser test
- [x] Per-panel Retry button: rebuilds the panel's 15-line chunk, regenerates the
      brief/prompt with the preceding chunk as context, re-renders on a fresh seed,
      timestamps untouched, progress persisted
- [ ] Reduce final video encoding from 1080p 30fps to 720p 24fps (browser + Colab encoder)

## Done
- [x] Final video encoding reduced to 1280x720 @ 24fps (was 1920x1080 @ 30fps)
