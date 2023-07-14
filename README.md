# Image from ISBN
A module for [ProcessWire](https://processwire.com/) CMS/CMF that uses a ISBN value to get a book cover image from [OpenLibray Covers API](https://openlibrary.org/dev/docs/api/covers) and populates it to a page before save.

This module requires 3 elements :
- A template where it should be used
- An image field where it should place the fetched image
- A *required* integer field where it should retrieve the ISBN to make a request for the cover image