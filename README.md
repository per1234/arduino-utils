# arduino-utils
Highly optimized arduino utility library for pin debouncing, rotary encoders, scheduled function execution and efficient debugging.

Content:
PinTrigger:
Register callbacks for button presses, or rotary encoders. Takes care of debouncing, uses by defualt uses pin-change interrupts, but can work witout inerrupts as well, if you need another library that needs pin-change-interrupts

FunctionScheduler:
Allows delayed execution of functions to avoid havint to use the arduino delay function 

Debug:
<<<<<<< HEAD
Contains a number of debug macros for logging. It allows asynchronous logging, so you can log from interrupt routines.
=======
Contains a number of debug macros for logging. It allows asynchronous logging, so you can log from interrupt routines.
>>>>>>> aa5040bf743903b348c41096440c3c07903ff248
