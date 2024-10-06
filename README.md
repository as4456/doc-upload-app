# A small full-stack app for document upload for learning purposes

## Backend

- [ ] Creation of users sign-up and sign-in POST endpoints
- [ ] Authenticated POST endpoint: Upload document of specific filetype only (e.g pdf)
- [ ] Authenticated GET endpoint: Retrieval of all user documents
- [ ] Authenticated DELETE endpoint: Delete a specific document
- [ ] Creation of Mongodb schema for storing users creds and documents metadata
- [ ] Upload documents to Amazon S3 using pre-signed URL
- [ ] ZOD validation for User creds: username, email and password
- [ ] Document uploads limited to 2 items and size of each <=2 mb in a day and no more than total of 10 items per user.

## Frontend

- [ ] A simple react app with sign-up/login form
- [ ] Debouncing logic for username creation
- [ ] File-picker to upload docs
- [ ] A user page showing a table of uploaded documents for a user with simple metadata, with delete button next to each doc
- [ ] A button to delete all documents
