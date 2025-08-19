.DEFAULT_GOAL := run
.PHONY: run stop
SHELL := /bin/bash

run:
	@docker compose up --build -d

stop:
	@docker compose down -v