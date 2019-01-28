# Mutex and Channel basics

### What is an atomic operation?
> An operation that cannot be interrupted

### What is a semaphore?
> A semaphore is a variable used to control access to common resources and it is useful for solving synchronization problems.

### What is a mutex?
> A mutex guaranteed only one thread accesses the shared variable at a time.

### What is the difference between a mutex and a binary semaphore?
> A mutex can only be released by the thread that acquired it, while any other thread can signal a binary semaphore.

### What is a critical section?
> A critical section is part of the program that accesses shared resources, and it can not be executed by more than one process at the time.

### What is the difference between race conditions and data races?
 > A race condition is a situation where the result of a concurrent program depends on the specific execution.
 A data race occurs when two threads access a shared memory location and at least one access is a write, the relative order of the two accesses is not fixed.

### List some advantages of using message passing over lock-based synchronization primitives.
> It is easier to build parallel hardware with message passing. And lock-based synchronization might create deadlocks.

### List some advantages of using lock-based synchronization primitives over message passing.
> lock-based synchronization could be faster.
