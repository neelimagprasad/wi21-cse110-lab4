
# Debugging

<img width="280" alt="Screen Shot 2021-01-30 at 12 48 26 PM" src="https://user-images.githubusercontent.com/50184924/106366899-252e3d00-62fc-11eb-80b2-4fe633ae26d2.png">
<img width="272" alt="Screen Shot 2021-01-30 at 12 41 25 PM" src="https://user-images.githubusercontent.com/50184924/106366904-2b241e00-62fc-11eb-83ae-8013003b58a2.png">

The bug was due to the fact num1 and num2 were taking the values of strings, so typecasting them to ints, then adding them resolved the problem. 

<img width="623" alt="Screen Shot 2021-01-30 at 1 01 21 PM" src="https://user-images.githubusercontent.com/50184924/106366895-21021f80-62fc-11eb-92dc-7b577a716a26.png">

Once it finishes downloading, answer the following questions:

1. What is the name of the new json file?
- citylots.json

2. Which file initiated the download of the new file?
- https://cse110lab4.herokkuapp.com/part2.js

3. What is its file size?
- 11.7 mb
4. How long did it take to download?
- 73 ms
Next, select that file to bring up a new side panel to answer the following:
5. What was your User-Agent for the browser that made the request?
- User-Agent: Mozilla/5.0 (Linux; Android 6.0; Nexus 5 Build/MRA58N) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/88.0.4324.96 Mobile Safari/537.36
6. In the response, what type of server did it come from?
- Server: Apache
7. When was the file last modified?
- Tue, 26 Jan 2021 22:14:13 GMT
8. What was the Content-Type of the file?
- application/json
9. Which method inside the initiating file made the request?
- fetchdata @part2.js:2
