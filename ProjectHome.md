Supports functions such as:
  * alarm`_`action() - setup function as timer handler
  * `_`alarm() - setup new alarm
  * alarm() - the same but wrapped with cli()/sei()
  * tclock() - like standard C's clock() but use timer number _timer_.
  * millis() - mseconds from last call
  * micros() - useconds from last call
  * etc...

Implemented for AVR Atmega128. All prototypes are in timers.h. Before use call init`_`timers() first!

Tested with WinAVR-20100110.