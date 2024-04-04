| mona86 by rudi/dke
| released 04.04.2024

Finally it's here - An x86 adaptation of ilmenit's Mona 250b procedural generator.

The original Atari XL version and detailed technique explanation can be
reached via Pouet ID: 62917

I painstakingly reconstructed the entire routine from scratch.
Beginning with a 32-bit C code adaptation on Windows.
I then fine-tuned it for smaller register sizes,
The only 32-bit register remaining is the seed handler.

No need to shave off more bytes - I've allready surpassed the 256-byte limit.

- Rudi
