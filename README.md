# Voting System

A minimal voting system made in the hexagonal architecture training with fastAPI taught by me.

Requirements:

* Python 3.10
* Pipenv

Install:

    pipenv install --dev

## REST

Run:

    pipenv run uvicorn app.main:app --reload

## Tests

Run tests (in `pipenv shell`):

    pytest

References: 
 - https://douwevandermeij.medium.com/hexagonal-architecture-in-python-7468c2606b63
 - https://medium.com/ssense-tech/hexagonal-architecture-there-are-always-two-sides-to-every-story-bc0780ed7d9c