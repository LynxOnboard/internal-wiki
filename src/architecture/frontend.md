# Frontend

## Responsibilities
- User experience
- State management
- API consumption
- Error handling

## Constraints
- No business logic duplication
- No direct database access (Some Exceptions See Below)
- API is the contract

## Exceptions
- Direct database access is authorized for:
    - Document uploads
    - Image uploads (avatar, gallery)
    - Authentication, send auth token to api for validation and caching jwt token