RS=rustc
RSFLAGS=-O

all: fp-safe harmonic partialsum

fp-safe: fp-safe.rs
	$(RS) -o $@ $@.rs $(RSFLAGS)

harmonics: harmonics.rs
	$(RS) -o $@ $@.rs $(RSFLAGS)

partialsum: partialsum.rs
	$(RS) -o $@ $@.rs $(RSFLAGS)

clean:
	rm fp-safe harmonic partialsum
