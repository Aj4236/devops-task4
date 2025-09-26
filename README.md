# DevOps Project – Task 4

A simple Nginx web page used to demonstrate Git best practices.

## Branches
- main — stable/release
- dev — integration
- feature/* — feature work

## Quick start
docker build -t task4-nginx .
docker run -p 8080:80 task4-nginx

