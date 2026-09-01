# SBAM Academic Hub

Phase 6 integration build for the SBAM Digital Campus concept.

## Included in this build
- Research Repository search/filter/details/favorites/offline cache
- SBAM Study area with **🔍 Subjects** and **🔍 All Subjects**
- Diploma / B.A. / M.A. subject browsing
- Cross-level subject search (for example: Vinaya)
- Smart Jump to subject results and official SBAM Learning Portal
- Official SBAM learning/news/resource links
- Teacher Admin review controls retained as a static/local prototype
- Extensible Campus Manager (`+ Add Campus`) as a local draft UI
- PWA manifest and local app icons
- Versioned service-worker cache with update-safe cache cleanup

## Security boundary
This static GitHub Pages build does **not** claim production authentication. Super Admin / Admin / Editor / Viewer roles, password hashing, server-side permission checks, publishing, audit logs, database backup and authoritative multi-campus records must be implemented in the server-side runtime before production use.

## Important preservation rule
`index.baseline-before-integration.html` is a byte-for-byte snapshot of the uploaded baseline used for this build. The working `index.html` is the integrated candidate.

## Official learning source
https://study.sbamdy.edu.mm/

## PWA
The manifest is `manifest.webmanifest`; icons are under `assets/icons/` and the service worker is `sw.js`.
