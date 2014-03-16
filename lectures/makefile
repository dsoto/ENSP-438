EXT = md
SRC = $(wildcard *.$(EXT))
PDFS = $(SRC:.md=.pdf)
all: $(PDFS)

%.pdf: %.md
	pandoc -t beamer $< -o $@

prefix = 438-lecture
slidebuild : $(prefix).md
	pandoc -t beamer -i $(prefix).md -o $(prefix).pdf

lecture:
	make slidebuild
	open -a /Applications/Adobe\ Reader.app/ $(prefix).pdf

past:
	cat lecture-*.md > 438-past-lectures.md
	make
