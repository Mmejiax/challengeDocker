# Task 7

## Description
flask app that counts web site visits and stored in a default Redis backend

## Tech stack
- python
  - flask
  - gunicorn
- redis

## Docker stack
- python:3.7-alpine
- redis:alpine

## To run
'docker-compose up -d'

## test application
'curl http://localhost/visitor'

## To stop (optional)
'docker-compose stop'

