.PONY: sentencetransformers
sentencetransformers:
	@echo "Creating virtual environment..."
	@conda env create --name sentencetransformers --file sentencetransformers.yml
	@echo "Virtual environment created."

.PONY: run
run:
	@echo "Running sentencetransformers..."
	bash run.sh
	@echo "sentencetransformers run."

# It is not working well by using command line. It only6 works with IDE like VSCode.
.PONY: test
test:
	@echo "Testing sentencetransformers..."
	bash test.sh
	@echo "sentencetransformers tested."