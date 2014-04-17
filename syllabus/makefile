prefix = 438-syllabus

all : $(prefix).html $(prefix).pdf $(prefix).md

$(prefix).md : $(prefix).jinja $(prefix).xlsx generate-syllabus.ipynb
	runipy generate-syllabus.ipynb

$(prefix).html : $(prefix).md
	pandoc -s -o $(prefix).html -c soto.css $(prefix).md

$(prefix).pdf : $(prefix).html
	wkpdf -m 36 -o $(prefix).pdf -s $(prefix).html

# add rules to make upcoming schedule
