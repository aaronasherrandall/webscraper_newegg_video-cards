# webscraper_newegg_video-cards
This webscraper runs on python and utilizes Beautiful Soup to parse html into containers for extracting data points in html.
It prints out a csv of said data points. 
The actual python file needs to be executed in a command prompt. 
I plan on testing this project on various sites for data extraction and then migrating it to run on a host.

Comments
For running on python 3.7 in Windows 10 environment, Shift + right-click run command prompt must be enabled. 
Successful run of this project required me to install pip install BeautifulSoup4 in command prompt.

First, locate python scripts folder on your computer, in my case:
cd C:\Users\USER\AppData\Local\Programs\Python\Python37-32\Scripts

Next, run: 
pip install BeautifulSoup4

Next, you should see a prompt similar to:
C:\Users\USER\AppData\Local\Programs\Python\Python37-32\Scripts>pip install BeautifulSoup4
Collecting BeautifulSoup4
  Downloading https://files.pythonhosted.org/packages/9e/d4/10f46e5cfac773e22707237bfcd51bbffeaf0a576b0a847ec7ab15bd7ace/beautifulsoup4-4.6.0-py3-none-any.whl (86kB)
    100% |████████████████████████████████| 92kB 828kB/s
Installing collected packages: BeautifulSoup4
Successfully installed BeautifulSoup4-4.6.0
You are using pip version 10.0.1, however version 18.0 is available.
You should consider upgrading via the 'python -m pip install --upgrade pip' command.

Switch back to the directory with webscraper .py file:
cd C:\Users\USER\Desktop\Web Crawler

Run python script (Windows 10):
py newegg_videocards.py

Script should run with CSV being printed in same directory as python file.

Note: I used Anaconda while building script to check for errors and to located data inside of containers for html parsing.

