# Concurrent rogramming in C++ using std::condition_variable
The following piece of code utilizes concurrent programming in C++ using std::condition_variable to create a producer and consumer. 
The producer initially sends a value to the consumer and then waits for the modified value from the consumer. 
Meanwhile, the consumer receives the value, modifies it, and sends it back to the producer, thus establishing an infinite loop. 
The aim is to produce sequential consistency.

