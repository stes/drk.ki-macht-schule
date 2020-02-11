page:
	mkdir -p docs
	mkdir -p docs/playground/dist
	mkdir -p docs/fairness

	find . -maxdepth 1 -type f -exec cp '{}' docs \;
	cp playground/dist/* docs/playground/dist
	cp fairness/* docs/fairness

show:
	chromium docs/index.html
