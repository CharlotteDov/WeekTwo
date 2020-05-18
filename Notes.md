Anaconda:

- Anaconda is a platform for data science work. By installing Anaconda, you get access to a series of tools for working in both the Python and R programming languages, plus excellent visual interfaces that reduce (some of) the pain of programming.
- Remember to look up anaconda command prompt in the search box to get the proper one, but regular command prompt worked better 

Wget:

- Wget is a program for downloading materials from the web
- Wget expects you to enter the URL to a webpage or some other online file
- mkdir wget-activehistory and cd wget-activehistory then wget http://activehistory.ca/papers/
- Helpful lingo: r recursive... np no-parent... -l links beyond domain we started in... -w wait time between requests to the server...--limit-rate= limit the bandwidth for our request (which necessarily slows down how long it’ll take to perform the request)
- Sublime text for images worked super well 
- Helpful hack for wget exercise: Put wget.exe in that folder. Click on the bar at the top of your file explorer that shows your location, so that it changes and you see the full path, eg c:\users\shawngraham\desktop\week2-thing . Copy that. Then open your command prompt or anaconda powershell. type cd and paste that path in, eg: cd c:\users\shawngraham\desktop\week2-thing. NOW you should be able to enter the command wget http://activehistory.ca/papers/ etc because the very first place that Windows will look for wget is in the folder you are invoking the command from. And it will find it, c

API:

- An API is just a way of opening up a program so that another program can interact with it. That is, instead of an interface meant for a human to interact with the machine, there’s an API to allow some other machine to interact with this one. If you’ve ever downloaded an app on your phone that allowed you to interact with Instagram (but wasn’t Instagram itself), that interaction was through Instagram’s API, for instance.
- Instead of you punching in the search terms on a search page, and copying and pasting the results, you frame a request as a URL. More or less. The results often come back to you in a text format where data is organized according to keys and values (JSON).
- Instructions are straightforward enough but would like to try it again to make sure I got it



