# Installation Instructions

## Dependencies

- Python 3.6 or higher
- Pip for Python 3
  - Django and Django-admin packages (pip)
  - Responses package (pip)

## Clone the repository

On a UNIX-style system (macOS and Linux), the command to clone the git repository should take the following form (assuming HTTPS is to be used)

`$ git clone https://csil-git1.cs.surrey.sfu.ca/bvhall/coursemapper.git`

## Making migrations

Within the root (highest) level of the local repository cloned previously, run the following command:

`$ python manage.py makemigrations && python manage.py migrate`

*Under some circumstances, Django may ask that you merge the migrations. In that case, run:*

`$ python manage.py makemigrations --merge && python manage.py migrate`

## Running CourseMapper

Within the root (highest) level of the local repository cloned previously, run the following command:

`$ python manage.py runserver`

This will start a local web-server that will allow you to test CourseMapper. Assuming you are running a standard networking configuration, entering the address:

`127.0.0.1:8000`

into your browser should bring up the CourseMapper greeter.

For more detailed instructions, please reference the provided video "Iteration_1_video.mp4"

## Running Tests

To run all automated tests, execute the following command:

`python manage.py test`
