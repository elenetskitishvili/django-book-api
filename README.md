# Django Book API

This is a learning project where I built a Book API using Django Rest Framework (DRF). The project includes the following features:

1. **Pagination**: I implemented pagination using DRF’s `PageNumberPagination` to limit the results to 10 books per page.
2. **Filtering**: I installed `django-filter` and added filtering functionality, allowing books to be filtered by `author` and `published_date`.
3. **Custom Permissions**: I created a custom permission class to restrict updates and deletions to the author of the book or an admin.

## What I Learned:
- How to implement pagination in Django Rest Framework.
- How to use `django-filter` for filtering API data.
- How to create and apply custom permissions in Django Rest Framework.
