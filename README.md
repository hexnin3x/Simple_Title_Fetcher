# Simple_Title_Fetcher

A python script to fetch title, status and content of urls in a list. The script uses beautiful soup for html parsing.

The script takes filename as a input and fetch list of urls from the user-defined filename. Currently the script fetches below details from the url : "list.txt" which contains following links: www.github.com, www.replit.com, www.youtube.com, www.facebook.com, www.twitter.com,

Example :

The URL's are in "list.txt"
<img width="1919" height="898" alt="image" src="https://github.com/user-attachments/assets/3a70e9f3-8072-4a26-bf11-8e3f78a489b0" />


Now we will run main.py and give the input as "list.txt":

python main.py list.txt
<img width="372" height="52" alt="image" src="https://github.com/user-attachments/assets/55614530-b2e3-4bcb-806f-6ea63ade7680" />


When we run this we will be welcomed with a banner "Title Fetcher" 
<img width="674" height="299" alt="image" src="https://github.com/user-attachments/assets/f7f0b12e-760f-4eeb-8785-b8f7722adb6b" />


Now the program will start to fetch data from the urls given

Once the program completely runs a new "responce.csv" file will be created responce created
<img width="1920" height="995" alt="image" src="https://github.com/user-attachments/assets/38a958bb-02f6-4fcb-b98b-c0623ef2d34e" />


"responce.csv" will contain all the fetched data from the urls:
<img width="1272" height="291" alt="image" src="https://github.com/user-attachments/assets/5f7242ea-a6d5-4d19-ae91-5efa1b37895a" />


python3
