Name:Mengesha Debash 
Id:DBUR/1260/10
Department:Software Engineering.
Name:Lidya Yohanis.
Id:DBUR/1240/10
Assignment II
QUESTION 1
If you run the homework app before implementing onSaveInstanceState(), what happens if you rotate the device?
Answer B, The counter is reset to 0, and the EditText no longer contains the text you entered.


QUESTION 2
What Activity lifecycle methods are called when a device-configuration change (such as rotation) occurs?

Answer C,Android shuts down your Activity by calling onPause(), onStop(), and onDestroy(), and
then starts it over again, calling onCreate(), onStart(), and onResume().

QUESTION 3
When in the Activity lifecycle is onSaveInstanceState() called? Choose one:

Answer A, onSaveInstanceState() is called before the onStop() method.

QUESTION 4
Which Activity lifecycle methods are best to use for saving data before the Activity is finished or destroyed? Choose one:
Answer A,          onPause() or onStop()
