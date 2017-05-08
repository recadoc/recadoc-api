# recadoc-api

`Recadoc-api` is proudly written in `django` and `django-rest-framework`.


## Development setup

Django needs the following setup for environment variables.

    export secret_key=<Your secret key>
    export debug=True

You may generate `secret_key` using following bash script

    cat /dev/urandom | tr -dc 'a-zA-Z0-9' | fold -w 64 | head -n 1
