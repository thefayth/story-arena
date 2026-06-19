# Status

Status: public export candidate.

## Current Public Surface

- Project documentation: ready
- Ownership files: ready
- Workflow diagrams: ready
- WordPress page draft: ready
- Visual asset audit: ready
- Hero/banner/social/icon assets: ready
- GitHub repository push: complete
- Live WordPress deploy verification: pending independent deploy smoke check

## Current Private Runtime

The canonical implementation remains the private WordPress plugin that serves `/ai-screenwriters/` on FaithCheltenham.com.

## Known Constraints

- The root project folder is not a git repository.
- The public export folder is its own git repository.
- The Codex process inherited stale proxy variables pointing at `127.0.0.1:9`; GitHub commands work after clearing `HTTP_PROXY`, `HTTPS_PROXY`, `ALL_PROXY`, and lowercase variants inside the command.
- GitHub repository is live at `https://github.com/thefayth/story-arena`.
- Server credentials and deployment systems are intentionally excluded from this public export.
