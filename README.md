<!--
https://readme42.com
-->


[![](https://img.shields.io/pypi/v/django-site-id-middleware.svg?maxAge=3600)](https://pypi.org/project/django-site-id-middleware/)
[![](https://img.shields.io/badge/License-Unlicense-blue.svg?longCache=True)](https://unlicense.org/)
[![](https://github.com/andrewp-as-is/django-site-id-middleware.py/workflows/tests42/badge.svg)](https://github.com/andrewp-as-is/django-site-id-middleware.py/actions)

### Installation
```bash
$ [sudo] pip install django-site-id-middleware
```

#### Cons
+   `django.contrib.syndication` not supported

#### Examples
`settings.py`

```python
MIDDLEWARE = [
    ...
    'django_site_id_middleware.middleware.SiteIdMiddleware'
    ...
]
```

<p align="center">
    <a href="https://readme42.com/">readme42.com</a>
</p>