.PHONY: install
install:
	poetry install

.PHONY: update
update:
	poetry update

.PHONY: lint
lint:
	poetry run pre-commit install && poetry run pre-commit run

.PHONY: local-run
local-run:
	poretry run python -m src.main
