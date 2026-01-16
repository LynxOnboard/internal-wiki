# Data Flow

## Typical request
1. Client sends request
2. API validates and authorizes
3. Cache checked (if applicable)
4. Database or vector search queried
5. Response returned

## Notes
- Auth happens early
- Errors are explicit
- Side effects are intentional