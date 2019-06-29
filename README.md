# BO-Attacks

Buffer overflow errors are characterized by the overwriting of memory fragments of the process,
which should have never been modified intentionally or unintentionally.
Overwriting values of the IP (Instruction Pointer), BP (Base Pointer) and other registers causes exceptions,
segmentation faults, and other errors to occur.
Usually these errors end execution of the application in an unexpected way.
Buffer overflow errors occur when we operate on buffers of char type.

Buffer overflows can consist of overflowing the stack (Stack overflow) or overflowing the heap (Heap overflow).
