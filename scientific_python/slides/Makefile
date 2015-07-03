.PHONY: slides clean

slides: Scientific\ Python\ Tools.slides.html
Scientific\ Python\ Tools.slides.html: Scientific\ Python\ Tools.ipynb reveal.tpl custom.tpl reveal.js
	ipython nbconvert --RevealHelpTransformer.url_prefix=reveal.js --to slides --template custom.tpl Scientific\ Python\ Tools.ipynb

clean:
	rm Scientific\ Python\ Tools.slides.html