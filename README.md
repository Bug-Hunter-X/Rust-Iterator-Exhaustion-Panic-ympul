# Rust Iterator Exhaustion Example

This repository demonstrates a common error in Rust: attempting to iterate past the end of an iterator.

The `bug.rs` file contains code that will panic because it tries to access elements from an exhausted iterator.  The `bugSolution.rs` file provides a corrected version that handles iterator exhaustion gracefully.

This example highlights the importance of checking for the end of an iterator before attempting to access further elements.