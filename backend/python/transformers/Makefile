.PONY: transformers
transformers:
	@echo "Creating virtual environment..."
	@conda env create --name transformers --file transformers.yml
	@echo "Virtual environment created."

.PONY: run
run:
	@echo "Running transformers..."
	bash run.sh
	@echo "transformers run."

# It is not working well by using command line. It only6 works with IDE like VSCode.
.PONY: test
test:
	@echo "Testing transformers..."
	bash test.sh
	@echo "transformers tested."