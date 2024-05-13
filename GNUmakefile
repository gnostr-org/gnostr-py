-:
	pipx install ./nostr --include-deps --force || \
		pipx reinstall ./nostr --python $(shell which python3)
	python3 ./setup.py install
	#pip  install .
	pipx ensurepath --force
rust:
	cd rust && \
		$(MAKE)
.PHONY: rust
