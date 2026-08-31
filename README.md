# SBAM Research Platform — Phase 6 Integration Candidate

This package integrates the student-facing Subjects / All Subjects / Smart Jump / Learning Portal navigation into a copy of the Phase 5 mobile build.

## Important preservation rule
`index.original.locked.html` is the preserved Phase 5 index. The new `index.html` is the Phase 6 integration candidate; the original is not overwritten.

## Student flow
- Subjects → Diploma / B.A. / M.A. → Class/Year → Subject
- All Subjects → search one subject across levels
- Smart Jump → quick return/search/official portal actions
- Official Learning Portal → https://study.sbamdy.edu.mm/

## Security honesty
The static package does not pretend to provide production authentication or server-side permissions. Super Admin / Admin / Editor / Viewer, password hashing, permission checks, audit logs, backup and publishing controls remain server-side requirements for the runtime deployment.

## Test status
Automated structural checks are run on the package build. Full runtime/API/authentication tests require the target laptop/server environment.
