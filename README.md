# winknot
Winknot is a program, rendered in Python, for Windows, that gives new names to commands that you use a lot. It is a port of Slipknot, which does the same thing for Linux. It has at its core the dream of ultimate user configurability, where the computer conforms to what you want, not the other way around.


It does this by tapping into a user-created database that contains a list of equivalence statements. 

An example: `word = c:\program files\microsoft office\office14\winword.exe`

Slipknot, when run, presents a prompt similar to a cmd.exe Command Prompt. With the above example, if you were to type `word` at the prompt and press enter, it would send the command `c:\program files\microsoft office\office14\winword.exe` to the operating system to execute (which is a fairly normal path for Microsoft Word).

If the user types something that doesn't show up in the database, it will pass the input to the system to execute. This means that you can treat Slipknot as a normal shell.

# install

To install this program, do the following things:


1. Make sure you have Python 2.7 installed, along with the standard libraries subprocess and os.
2. Clone this repo into some otherwise empty folder.
3. Edit some environment variables. This option is in Control Panel > System > Advanced tab > Environment variables. This might vary on some versions of Windows; Google it if you have questions.
  - Add a variable called SLIPKNOT_HOME, and set it equal to the path to the folder that you put Winknot into.
  - Edit the path to include this location as well.
4. If you want to use the included launcher, compile the file `slipnkot.cpp` with your favorite C++ compiler.
5. Enjoy!


If it does fail, please copy and paste the entire callback into an Issue. I really appreciate bug reporting. If you feel like fixing it, cool. Make a fork, fix it, and put in a pull request. You know the drill.


I did make a launcher that you can move around to wherever you want. It's in here just as slipknot, and is compiled from slipknot.cpp. This launcher is mobile, so you can put it in your executable path and use it as you would a normal executable.


My Twitter handle is @69codewars. Let me know, over Twitter or GitHub, if there are any problems.


Thanks!


~C
