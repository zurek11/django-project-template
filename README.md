# Django project template

Simple quickstart for [Django](https://www.djangoproject.com/)-based projects created as
[cookiecutter](https://github.com/cookiecutter/cookiecutter) template.

## What's inside?

- Exception handling (`ApiException`, `ValidationException`
  prepared for [django_api_forms](https://github.com/Sibyx/django_api_forms))
- Basic security (signature middleware, Argon password hasher)
- Hard/soft delete for models
- Custom `User` model
- Response objects (`SingleResponse`, `ValidationResponse`)
- Custom JSON encoder prepared for [porcupine-python](https://github.com/zurek11/porcupine-python) serializer
- Configuration using `.env` files
- [Sentry](https://sentry.io/welcome) integration
- Dependency management using [poetry](https://python-poetry.org/)
- Multi-environment settings

### Bundled dependencies

- [django_api_forms](https://github.com/Sibyx/django_api_forms): Request validation
- [python-dotenv](https://github.com/theskumar/python-dotenv): `.env` handling
- [django-enum-choices](https://github.com/HackSoftware/django-enum-choices): Enums in Django models
- [porcupine-python](https://github.com/zurek11/porcupine-python): Response serialisation
- [django-imap-backend](https://github.com/Sibyx/django-imap-backend): Custom e-mail backend for simplified testing

## Usage

You need to have installed [cookiecutter](https://github.com/cookiecutter/cookiecutter) in your system, then you can
call:

```shell
cookiecutter gh:backbonesk/django-project-template
```

---
Made with ❤️ and ☕️ BACKBONE s.r.o. (c) 2021
