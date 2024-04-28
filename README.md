# Django Training Arc
A Django Workshop Session for UP Mindanao SPARCS. This will follow the official Django Documentation Tutorial [https://docs.djangoproject.com/en/5.0/intro/tutorial01/](https://docs.djangoproject.com/en/5.0/intro/tutorial01/). Follow the commands below to setup your local environment to follow along the workshop.

## Setup Environment
1. ### Make sure Python 3.10 is installed in your machine.
2. ### Install pipenv
    - Follow the docs for installing [here](https://pipenv.pypa.io/en/latest/installation.html).
    - or use the commands
        ```shell
            pip install pipenv --user
        ```
2. ### Clone the Repo
    ```shell
        git clone https://github.com/ArJSarmiento/Django-Training-Arc.git
    ```
3. ### Install the dependencies
    ```shell
        cd Django-Training-Arc
        pipenv install
    ```
4. ### Activate the Virtual Environment
    ```shell
        pipenv shell
    ```
5. ### Make migrations
    ```shell
        python manage.py makemigrations
    ```
6. ### Migrate the database
    ```shell
        python manage.py migrate
    ```
7. ### Run the server
    ```shell
        python manage.py runserver
    ```
