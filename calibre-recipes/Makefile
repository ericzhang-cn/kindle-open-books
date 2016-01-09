RECIPES := $(shell /bin/ls -A *.recipe)

all: $(RECIPES:.recipe=.mobi)

%.mobi: %.recipe
	ebook-convert $< $@

.PHONY: clean

clean:
	$(RM) *.mobi
