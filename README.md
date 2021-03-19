# Ridiculously Simple App Engine + Flask

Absolutely the simplest App Engine and Flask web app I could imagine.

No backend. A simple entry point and Jinja template.

Static files go in the /static folder. Nothing but a favicon.

## Setup

Install:
 * [Python 3.9](https://www.python.org/downloads)
 * [Google Cloud SDK](https://cloud.google.com/sdk/docs/install)
 * [pip](https://pip.pypa.io/en/stable/installing)

Install flask:
 	pip install

## Local server server

	python main.py

## Deploying

Replace [app id] with your very own App Engine id.

	gcloud app deploy app.yaml --project [app id] --version 1

## Why did I do this?

This is part of a series of ridiculously simple, executable code examples. 

Sometimes we need to cut through the documentation jungle and start making stuff.

## Credits

Jude Osborn
