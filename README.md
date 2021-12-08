# Activities-Intents

Added a button "Send"
Added a Second Activity with a textView "Message Received".
Modified the AndroidManifest.xml file.
Added an Intent to the Main Activity.
Added an EditText to the MainActivity layout.
Added a TextView to SecondActivity to display message.
Modified SecondActivity to get the extras and also display the message.
Added an EditText and a Button to the SecondActivity layout.
Created a Second Activity response Intent.
Added reply by the TextView elements.
Displayed the reply from the Intent extra.

Homework Questions:

Question 1
What changes are made when you add a second Activity to your app by choosing File > New > Activity and an Activity template?
The second Activity is added as a Java class, the XML layout file is created, and the AndroidManifest.xml file is changed to declare a second Activity.

Question 2
What happens if you remove the android:parentActivityName and the <meta-data> elements from the second Activity declaration in the AndroidManifest.xml file? 
The Up button in the app bar no longer appears in the second Activity to send the user back to the parent Activity.

Question 3
Which constructor method do you use to create a new explicit Intent?
new Intent(Context context, Class<?> class)

Question 4
In the HelloToast app homework, how do you add the current value of the count to the Intent?
As an Intent extra

Qustion 5
In the HelloToast app homework, how do you display the current count in the second "Hello" Activity? 
Get the current count value out of the Intent.