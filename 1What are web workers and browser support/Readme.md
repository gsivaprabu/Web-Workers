#What are web workers and browser support

- Background threads in the web browsers.
- It will run independedntly in the UI.

### Two types of web workers.
- Dedicated.
		- Linked to the web browser window, so it has a very tight relationship with that window.
- Shared.
		- A shared worker is a worker that runs in the background and basically any scripts that runningwithin that domain can send messages to that worker.
- Dedicated workers as shared workers are largely unimplemented in any of the browsers at the time of recording.

- Web workers basically a thread, that works within the browser.
- Take the ability to take some sort of processing and have it run in the background.

###  Limitations

1. You have no access to the DOM.
2. Cant get any of the HTML,any input fields.
3. Window few read only exceptions.
4. You don't have access to the hos page.
5. Your famous libraries (jQuery..) not work with web workers.
6. jquery.ajax not working.
7. We can try native script (XmlHttpRequest) only
8. Access the Navigator APP
9. Timers are allowed.

### References

1.[How to process Large Volumes of Data in JavaScript](http://bit.ly/r5BSTI)
2.[Javascript Timer-Based Pseudo-Threading](http://bit.ly/oiOiLT)

