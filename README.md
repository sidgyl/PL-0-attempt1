Understanding of Pascal and elementary compiler/interpreter concepts.
Requirements:
1. Add simple I/O to PL/0 (plzero.pas) as an input stream (in) and an output stream (out).
a. An integer may be read from the input stream by using in as an r-value.
b. An integer may be written to the output stream by using out as an l-value.
c. The actual input stream will be as integers, one per line. -999999 will end the stream and will be supplied to the PL/0 program once. Attempting to access the input stream after -999999 will abort. “?” should be used as a prompt.
d. The output stream will be integers written one per line. Each output line should begin with “!”.
e. The output stream does not terminate.
f. “in” and “out” are identifiers for the streams. These are not reserved words and may be “masked” by other declarations.