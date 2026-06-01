# OptiFlex
ASI plugin to add Reflex markers to games that lack them. Designed for use with OptiScaler to translate Reflex to AL2/XeLL 

This needs a per-game implementation by finding input polling and simulation thread logic in a compiled binary, and then using those to implement Reflex. This is exactly how Anti-Lag+ functioned.

Since it's implemented at such a low level, it should support anything that uses the Reflex API. That means SpecialK, OptiScaler (through fakenvapi), and other stuff I guess. And it will actually reduce latency unlike RTSS Reflex injection or whatever.
