# django-todo-react
Following [this tutorial](https://www.digitalocean.com/community/tutorials/build-a-to-do-application-using-django-and-react)

## Notes
### django's manage.py
python manage.py
- `startapp <app name>`: new app (component)
- `migrate` run (all unmigrated?) migrations
  - this includes users, permissions, groups, audit logs, sessions
- `runserver`: run server
- `makemigrations <app name>`: creates a migration script based on the `model.py` of the `<app name>`
- `migrate <app name>`: run migrations in `migrations` folder of `<app name>`
- `createsuperuser`: creates a user in the `auth_user` table