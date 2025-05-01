# Reader-Writer-Synchronization

"The Reader-Writers Problem of Threads with Locks/Semaphores"

This project simulates the classic Reader-Writer Problem, a common concurrency control issue in operating systems. Implemented in C++ using threads, mutexes, and condition variables, the program allows multiple readers to access shared data concurrently, while ensuring exclusive access for writers. It prevents race conditions and prioritizes proper synchronization by using flags and counters to control read/write access. The interactive console-based interface prompts users to choose a reader or writer role and simulates scenarios where writing is blocked if readers are active and vice versa.
