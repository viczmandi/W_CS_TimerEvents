# W_CS_TimerEvents

Using Visual Studio, create a new Windows Forms application project. Name the project TimerEvents.

Add a ProgressBar control to the form.

Within the form class declaration, declare an instance of a System.Windows .Forms.Timer object. Timer objects can be used to throw events after a specified number of milliseconds. 

In the designer, view the properties for the form. Then view the list of events. Double-click the Load event to automatically create an event handler that will run the first time the form is initialized. Within the method, initialize the Timer object, set the interval to one second, create an event handler for the Tick event, and start the timer.

Implement the method that will respond to the Timer.Tick event. When the event occurs, add 10 to the ProgressBar.Value attribute. Then stop the timer if the ProgressBar.Value attribute has reached 100.
