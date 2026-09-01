# SBAM Academic Hub — Final Stable Candidate

This build is based on the uploaded GitHub source and keeps `index.baseline-before-integration.html` as a byte-for-byte preservation snapshot.

## Integrated student features
- 🔍 Subjects — normal level browsing
- 🔍 All Subjects — cross-level subject search
- Diploma / B.A. / M.A.
- Example: searching **Vinaya** returns Diploma, B.A. and M.A. entries
- ⚡ Smart Jump to the matching subject result
- 📚 SBAM Learning Portal official-source link
- 🔬 Research Repository search/filter/details/favorites/offline cache
- 🏫 Existing official campuses + future `+ Add Campus` draft architecture
- 🔐 Super Admin → future Admin / Editor / Viewer role architecture
- 📱 PWA manifest + 192/512 icons using the user-provided logo
- 💾 Versioned service-worker cache

## Important security boundary
This GitHub Pages build is a static client-side application. It does **not** claim production authentication or server-side security. Production password hashing, role enforcement, authoritative Add/Publish workflow, audit logs, database backup and multi-campus synchronization belong in the backend runtime.

## Official learning source
https://study.sbamdy.edu.mm/
