# Debouncing_and_throttling

Debouncing is a programming practice used to ensure that time-consuming tasks do not fire so often, that it stalls the performance of the web page. In other words, it limits the rate at which a function gets invoked.

Debouncing in JavaScript is a practice used to improve browser performance. There might be some functionality in a web page that requires time-consuming computations. If such a method is invoked frequently, it might greatly affect the performance of the browser, as JavaScript is a single-threaded language. 


Throttling or sometimes also called throttle function is a practice used in websites. Throttling is used to call a function after every millisecond or a particular interval of time only the first click is executed immediately.

Let’s see, what will happen if the throttle function is not present on the web page. Then the number of times a button is clicked the function will be called the same number of times. Consider the example.

Without throttling Function: In this code suppose the button is clicked 500 times then the function will be clicked 500 times this is controlled by a throttling function.
