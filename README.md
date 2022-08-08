# django_heroku_deployguide
guide for deploying a django site with heroku

cookingbook:
1. change debug to false in setting.py
2. collect static files "python manage.py collectstatic"
3. deploy git branc in heroku
4.

cli for debuging(prolly needed..):
1. log in with "heroku login" command in cmd.
2. run "heroku logs --tail --app "website-name""
