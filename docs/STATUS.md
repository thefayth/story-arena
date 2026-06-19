# Status

Status: public export candidate.

## Current Public Surface

- Project documentation: ready
- Ownership files: ready
- Workflow diagrams: ready
- WordPress page draft: ready
- Visual asset audit: ready
- Hero/banner/social/icon assets: ready
- GitHub repository push: pending GitHub CLI auth or repository-create connector access
- Live WordPress deploy verification: pending independent deploy smoke check

## Current Private Runtime

The canonical implementation remains the private WordPress plugin that serves `/ai-screenwriters/` on FaithCheltenham.com.

## Known Constraints

- The local folder is not a git repository.
- GitHub CLI currently reports the saved `thefayth` token as invalid.
- GitHub connector returned `404 Not Found` for `thefayth/story-arena`, so the chosen slug appears available or at least not accessible as an existing public repository.
- Server credentials and deployment systems are intentionally excluded from this public export.
