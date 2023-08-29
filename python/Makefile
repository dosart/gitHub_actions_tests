.PHONY: install run_app run_tests tests app down

install:
	@echo "Install dependencies"

run_app:
	@python3 src/main.py

run_tests:
	@echo "Make tests"

tests:
	@docker-compose up tests

app:
	@docker-compose up app

down:
	@docker-compose down
