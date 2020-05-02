PAPER_NAME = paper
PAPER_MAIN_SOURCE = $(PAPER_NAME).tex

.PHONY: all
all: paper

.PHONY: paper
paper:
	rubber --unsafe --pdf $(PAPER_MAIN_SOURCE)

.PHONY: clean
clean:
	rubber --clean --pdf $(PAPER_MAIN_SOURCE)
