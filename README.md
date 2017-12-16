Android app that leverages the OpenLibrary API to search books and display cover images. It also allows you to recommend books to friends. See the Book Search Tutorial on our cliffnotes for a step-by-step tutorial.

The app is composed of two screens. The first screen displays a list of books, in which, each book is described by its title, author and cover photo. After a user selects a book from the list, a second screen appears displaying additional details about the book, including the publisher and no. of pages.
Overview
The app does the following:

Search a list of books using the OpenLibrary Search API
Display the list of books with their cover images and details
Replace ActionBar with Toolbar
Use SearchView to search for books with a title
Show ProgressBar before each network request
Add a detail view to display more information about the selected book from the list
Use a share intent to recommend a book to friends
