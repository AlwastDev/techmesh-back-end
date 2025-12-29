# TechMesh MVP Gate (Backend)

MVP is shipped when ALL items below are ✅.

## API surface (must exist and be stable)
- [ ] Auth: session/JWT endpoints (plus test-mode auth for E2E)
- [ ] Users: GET /me; GET /users/:handle
- [ ] Profile: PATCH /me/profile
- [ ] Skills: list + update user skills
- [ ] Projects: CRUD
- [ ] Connections: send/cancel/accept/decline + list connections/requests
- [ ] Posts: create + feed list with cursor pagination
- [ ] Reactions: like/unlike (unique per user/post)
- [ ] Comments: create + list

## Data integrity (must be enforced)
- [ ] Unique handle
- [ ] Prevent duplicate connection requests
- [ ] Prevent liking twice (unique constraint)
- [ ] Authorization checks for all writes

## Tests (minimum bar)
- [ ] Unit tests for connection request state transitions
- [ ] Integration tests for core endpoints with real DB (test database)
