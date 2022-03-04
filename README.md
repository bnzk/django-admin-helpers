# django-user-utils
various user related tools for django:

- enable password reset for admin users (through existing urls, provided by django.contrib.auth)
- simplify user editing: hide email field, username is an emailadress. dont change any underlying mechanics provided by django.contrib.admin
- integrate django-separate-users: proxy models for frontend user and admin user, to allow normal admin users to edit other admin users, and/or frontend users
- wish: create new admin users without password, send reset link/welcome email? 


inspiration

- https://github.com/etianen/django-usertools
- https://github.com/bnzk/django-separate-users
