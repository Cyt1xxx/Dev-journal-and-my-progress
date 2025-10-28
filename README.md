# Dev-journal-and-my-progress
Keeping working to improve myself at programming , posting my results of studying sessions particulary every day.
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

10.09.2025(6-7h)
1) Watched video about difference mutable and immutable objects, compared it with Docker layers, refactored code, added argparse object + importlib to use dynamic module loading for universal structure to imlement it to docker, started refactoring code with oop
2) May be could do more coding rather then watching a video`s, but anyway it was helpful, not all , but many
3) Was focused, didn`t get distracted

11.09.2025(6h)
1) Refactored whole code with OOP classes , understand what self in OOP init method is, repeated encapsulation in OOP, implemented dynamic loading of modules, watched video about when to use OOP , when functions, started building Docker file
2) May be I could do the better readablity of code, as I added OOP classes here became more places to work with
3) Eventually mastered in practise OOP classes , correctly done dynamic loading.

12.09.2025-15.09.2025(didn't log my progress due to family circumstances, sorry, i coded this days but fewer) 
1) All in all what I've done this days: build Dockerfile , started exploring network low level principles inside the container, see what volume in docker is, was getting into SOLID and practising OOP approach except functional that I've always used to follow. Started building new project of scraper with framework,
rebuilt exsisting architecture
2) Didn't have enought time for coding , worked 3-4 h per day
3) Understood importance of OOP , readable, maintainable code in application. Got into OOP , I didn't understand it so good before and used

16.09.2025(6-7h)
1) Started implementing SOLID principles to main softwarer, refactor fetcher module using class approach, learned about usage abstract classes and methods and encapsulation.
Refactored API sending classes with knowledge of Inheritance , Dependency injection , open|closed , single responsibility principles and repeated usage of *args , **kwargs 
3) Was hard understanding OOP approach as I never used it before just theory.
4) Glad to practise new more robust and scalable approach

17.09.2025(4-5h)
1) Explored Inheritance\polymorphism usage in theory, classmethods, staticmethods , wrappers , composition , class variables. Refactored a bit db logic classes.
2) Few practise and was unaware to make changes, didn't know how to implement changes.
3) Finally understood and explored wrappers

18.09.2025-24.09.2025
Was in vacation during this time lapse. Did some small refactoring before trip

25.09.2025(6h)
1. Was refactoring DB logic with SOLID principles anc OOP approach. Fully understand how actually decorator work's, practised ABC , Inheritance, learned about Dependency Injection, practised interface segregation principle.
2. That was challenging to get to work from a vaccation xD but I coped with it
3. Getting more into OOP approach and SOLID by testing it and writing code, more understand how to build classed modules 

26.09.2025(6h)
1. Refactored whole DB.py module using OOP + solid. Learned about Dependency Inversion and Injection combining Composition in OOP class, was mastering low level SQLalchemy classes such as engine and connection to make better code and understand all principles
2. Could do more code and learn more, struggled to understand about Dependency Inversio
3. Did good code

27.09.2025(3h)
1. Refactored only 1 function, more time read SQLalchemy docs about update with WHERE clause, low level , how session's work, about transaction's , stetes of objects such as: transient , pending , persistent
2. Too much theory , few practise, was distracted IRL
3. Understand depeer SQLalchemy

28.09.2025(4h)
1. Was getting into SQLalchemy low level principles. Learned about UoW pattern , what is it, where it used; understand how flush works and commit after it; Identity Map , how db object's being transisient into python's , how it stored in memory. Understanding more refactored 2 methods in db class
2. Could spent more time for working
3. Good balance practice and theory

29.09.2025-04.10.2025
Had been relocating to another country

05.10.2025(3-4h)
1. Setted up my work enviroment, was remembering where I stopped in my project and getting around it, finished refactoring one module with OOP , started the same thing with another, done partly everything
2. Could be more focused at the end of work and less distracted by music , yt shorts and other, it was really hard to comeback
3. Did good job , found mistakes and refactored it, learned in practise LSP and why we need to use it

06.10.2025(3-4h)
1. Refactored whole core scraper module , following SOLID principles, changed existing modules, prepared for implementation to main orchestratot func
2. May be could code more, still procrastinating after relocation
3. Did focused refactoring , but could be focused more

07.10.2025(3-4h)
1. Was mastering mainly SOLID principles as LSP , ISP, DIP. Started making logic of scraper orchestrator.
2. Too much theory , less practice, could spend more time on programming
3. Understood pretty everything about mentioned solid principles.

08.10.2025(3h)
1. Made general url management module that captures it classes and orchestrator of url creation.
2. As yesterday, a little anxious and uncomfortable because of the move.
3. Investigated my weak skilss in OOP , working on it

09.10.2025 Day off

10.10.2025(3-4h)
1. Refactored catalogue scraper functions to class Approach, applied DIP, Composition, DI, SRP for it
2. Sorry don't remember writing all in 1 day (10 and 11 day of coding)

11.10.2025(6-6.5h)
1. Changed all scraper tasks functions to class Approach , think of new technical task, how to scale software, refactored existent bugs and made small changes, was exploring some architectural patterns like Repository pattern, understood how to properly use ABC interface class
2. All good)
3. Boosted my programming hours twice, returned hours of programming from my previous location

12.10.2025 day off

13.10.2025(4-5h)
1. Started refactoring another pipeline, refactored half of existing functions to SOLID approach, changed 1 module to OOP SOLID approach, was mainly practicing SOLID and refactoring. Explored the difference between __add__ , __iadd__ in python memory concept. Extending and reassigning objects
2. Could spend more hours coding and refactoring
3. Did many changes

14.10.2025(5h)
1. Read article about property() decorator in OOP , watched the difference between ABC and Protocol, started exploring how actually relationship works in SQLalchemy, repeated forgetten thing, added new table
2. Only theory , less coding
3. Did good theoretical practise , understood some mind-blowing concepts

15.10.2025
Burned out , day off

16.10.2025 (6h)
1. Learned and implemented to code Stratagy and Repository pattern's, refactored pretty all db module.
2. Can finish all module and started refactoring because there are a lot of work. Lack in knowledge in SQLalchemy...
3. Did good , focused work for 6h

17-19.10.2025(Procrastinating days worked a little, added insignificant changes)

20.10.2025(2-3h)
1. Practised on sqlite3 module , explored about relationship in SA, session management, ON CONFLICT DO NOTHING/DO UPDATE , tested both, started thinking of benefits to change to Postgres , learned about BULK INSERT , how to optimize db commands in postgres, dialect of postgres insert
2. Didn't find more time for programming
3. Understood the key factor of vulnerable place in my software , worked on better understanding the background principles

21.10.2025(2.30h)
1. Watched Ajran codes video about type hints, why we use them. https://tinyurl.com/2xbkpy9n , refactore hardly all repository, it remained only to handle db logic inside the runner, understood how to optimize asyncio tasks by creating each method for I/O task, implemented queue inside the pipeline , added pipeline pattern.
2. Again -> Didn't find more time for programming
3. Good returning in coding routine after a rest

22-23.10.2025(some small commits , procrastinated)

24.10.2025(4-5h)
1. Learned about #Generators , when to use over list comrehension [yt_link](https://youtu.be/RvQkEaBMTJc): it generally needed when we wanna fetch huge amount of data and we mainly don't know where the end would be,we can only iterate through result once, it is memory efficient approach over lists, as the results of object aren't store in memory. Read till the end article about asyncio, explored and reapeated concepts, learned about asyncio for loop, how asyncio.gather(return_exceptions = True) works, Exception group, except*: it used to catch more than one Exception , all exceptions are being stored in ExceptionGroup() object, and using except* (with asteriks) it can catch certain error and get exceptions by accesing property "exceptions" , return_exceptions = True allows us to catch more then 1 error in loop. how to handle many errors in concurrent app [article](https://realpython.com/async-io-python/#common-async-io-programming-patterns) , added new class of advert status management (uses db update commands in while loop) and account manager that extracts tokens from log:pass
2. Still theory > practise. Must have more practise and less procrastination
3. Good theoretical pracitse, practised and got more into asyncio, generator's

25.10.2025(3 h)
1. Created new plan for applying enhancements inside my application (The most prioritized task is to create new database - postgres , set up database migration tool - alembic) , with that being said I started learning postgres principles , installed it agaian to new enviroment, started getting deeply into in by reading docs, learned about Multi Version Concurrency Control tool inside of postgres , the main purpose of it to avoid deadlock inside the database , learned about VACUM that cleanes oldest versions of snapshots.
2. Could make more time for studying
3. Coocked food for a week , did sport , made a plan for updating a software

26.10.2025(2h)
1. Installed postgres , started reading it's docs, watched introduction to postgres video
2. Idiot. Could make more time for studying
3. -

27.10.2025(burned out)

28.10.25(3-3.5
1. Again I have been getting into postgres, but only the terms related to my app. The study was regarding of ACID , most of all Isolation. Explored about levels of isolation , phenomena that is prohibited. Fully understood: dirty read , read commited lvl , phantom read.
Dirty read - READ clause of uncomitted concurrent transaction , unreal in postgres, because of MVCC aspect, as each read stmt reads the last commited version of choosen row.
Phantom read - when between two read stmt's happen a WRITE transaction, that was commited and the transaction after WRITE stmt would show us new row added/modified, so the phantom row. In other words, when concurrent transaction is made between transaction with read stmt's. It is fixed with isolation's lvls such as: repeatable read + serializable.
From postgres [docs](https://www.postgresql.org/docs/18/transaction-iso.html): A transaction re-executes a query returning a set of rows that satisfy a search condition and finds that the set of rows satisfying the condition has changed due to another recently-committed transaction.
3. Might considered more lvl into today's study
4. Good destination switchment movement as I don't need to read all postgres concepts, only regards my project
