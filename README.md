# About
In this program, the function handle_sigint is registered as the signal handler for SIGINT using the signal function. The main program runs an infinite loop that prints "Running..." and then sleeps for one second. When the user presses ^C, the program will receive the SIGINT signal, which will trigger the handle_sigint signal handler. The signal handler will print a message indicating that the signal was caught.

Note that in modern systems, the signal function is considered outdated and it is recommended to use the sigaction function instead, as it provides more control over how signals are handled.
