# Dev-journal-and-my-progress
Keeping working to improve myself at programmin , posting my results of studying sessions particulary every day.
Previous dev.journal was in my diary , written by hand.
1 - everything what i did during a day
2 - struggles , problems , or some distractions
3 - pluses, benefit , pros, that i completed well 

01.09.2025 Programming hours: 7-7.5h
1) Finally understood advanced logging features and imlemented to my project , set up new logger config for SA , web scraper logs and main script logs + db;
   Fixed bugs with asyncio tasks runner to run 2 tasks + concurrentlty with cooldown in while True loop;
   Made custom request headers settings , refactored a bit all of code;
   Changed fetcher of pages
2) Was struggling with advanced logging features , did it for 3 hours, read docs , stack , watched youtube , finally did it. Other problems were solved in quite short period of time
3) Other problems were solved in quite short period of time.

02.09.2025 Programming hours: 6-6.5 h
1) Changed parsing mode to other website, successfully working, during transition mastered a bit of datetime module as : timedelta , timezone , fromtimestamp , unix timestamp computer time to human readable.
   Added mini docs as string description for mainly each func, repeated urlib , how it works and parses / collecting url , with & separator and = sign. Refactored some existing funcs , repeated dict comprehension.
2) A lot of theory - fewere practise and code , could do a lot more
3) Good that when I had problem with some module I tried not just copying code from forum without understanding , but to read docs , test it in other situations with other behaviour. But didn`t have a balance xD
   
03.09.2025 Day off

04.09.2025 (5.30-6h)
1) Refactored the main software code , still there are problems, was repeating OOP principles , learned abut dequeue , why it is more efficient sometimes then list for non-memorizing task , where data need to be processed immideately , i.e don`t necessary to be stored for a while
2) Again , was struggling with choosing the right proxy servise , lost money on efforts , was just thinking for 3-4 h just how to do it without trying actually to write a code
3) Finally I decided how to do it , made 50% of logic , but it was already too late

05.09.2025 (5h)
1) Unfortunaly, no code today , was existed about cyber security topics such as: XSS , WAF , how to prevent abusing your API for malicious tasks, refactored code a bit , there was a critical error with While loop in coroutine + prevent db blocking and working with each task with asyncio.Lock in software.
2) Didn`t finish Proxy manage , a bit of bored and lazy today
3) I explored a lot new info that can help me in buildings my API`s and providing them security , noticied critical errors

06.09.2025(3 h)
1) Today was 1 launch of my software, all worked pretty good, but was several bugs , fixed it then make some refactors with db logic and added some features in scraper and all software , now there are more parametrs in config to set such as MAX_URL_TO_SKAN , when soft raises this page it stoppes the while loop.
Was thinking about further architecture of software , deployment , features , UI. Finally, came to decission.
2) All good , but I can spend more time coding.
3) Fixed all bugs very quickly

07.09.2025(6h)
1) Again was thinking about containerization, tested my code again, explored log`s from logging results. Started learning about Docker , watched tutorial video, set up docker , WSL , did docker guide tasks, using their code examples.
2) Didn`t write code at all , could do programming more
3) Explored a lot of about docker , it is new tool for me, will set up to my project in few days

08.09.2025(5h)
1) Was exploring what the docker is. Whatched getting start videos, downloaded docker , did some tutorial tasks for beginners. Changed time in my software to unix format, read how sqlite interracts with datetime, eventually found that it hasn`t datetime type of data in columns, fixed bugs
2) Doomscrolled a bit and watched social media during coding process
3) Did everything what planned for day

09.09.2025(6 h)
1) Whole day was reading docs about docker. Understand what is image, container, docker daemon , how it is structured, that it uses linux kernel, how does it interact with other docker parst using REST API structure, docker compose (multi containers) ,layers , why it is memory efficient. Started doing dockerfile in my project
2) Could do more, didn`t fixed some bugs in code , still need refactor.
3) Well done theory learning.
