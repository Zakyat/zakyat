# zakyat

There are separate servers for the backend and the frontend. SSR is achieved through Nuxt requesting the data from the Django app. Docker is used for a consistent and easy-to-use development environment.

## Configuration
Create a file in the root directory called ".env" and add the following environment variables, filling in values for the username and password:
```bash
POSTGRES_USER=
POSTGRES_PASSWORD=
POSTGRES_DB=zakat_db
```
Follow any additional instructions in the submodules.

## Running

To run this project, simply run `docker-compose up` and then check [localhost](http://localhost). 

## Documentation

The requirements and documentation can be found [here](https://docs.google.com/document/d/1z1xyGixq2cfKc5W9Oyifu96NMFANsg9mGpXQVyeBtjg/edit#heading=h.6w263tjhlg79) in Russian.
