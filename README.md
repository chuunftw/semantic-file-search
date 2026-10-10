# semantic-file-search

Local Semantic File Search

A senior design project to build a Windows desktop application that helps users find files on their computer by describing what they are looking for.

Project Overview

People often remember what a file contains but forget its filename or location. Our app will combine semantic search with filename and keyword search, allowing users to search by meaning instead of relying only on exact words.

For example, a user could search for “my notes about renewable energy” or “a photo of a red car” and receive relevant files from their selected folders.

Planned Features

- Select which folders the app can access and index.

- Search text, documents, and images using natural-language descriptions.

- Search by filename and keywords.

- Display ranked results with file information and locations.

- Open results in their default Windows applications.

- Update the index when files are added, changed, or removed.

- Video search is outside the current scope, and GIF support is deferred.

How It Works

The app will scan supported files, extract searchable content, and use local AI models to represent their meaning as numerical embeddings. These embeddings and file details will be stored in a local index that the app searches when a user submits a query.

Privacy and Local Processing

The app is designed to process files and queries locally, keep its index on the user’s computer, and access only user-approved folders while respecting Windows file permissions.
