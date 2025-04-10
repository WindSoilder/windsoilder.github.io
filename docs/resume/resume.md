Keith Chen
Back-End Engineer

WindSoilder@outlook.com
https://github.com/WindSoilder

# Profile
I am a experience software engineer, mainly working as a backend engineer, programming in python and rust.  With strong experience in back-end development, design RESTFUL api independently.  As well as collaborate with team member using agile methodologies.

Personally, I'm care about unit testing, documentation, writing readable and testable code.

Fan of solving problems, writing code, and contributing to open source projects.

# Skills
programming languages: python, rust.

Back-End Framework and Databases: flask/fastapi, celery, mongodb, mysql, redis, rabbitmq(mainly used with celery)

Testing and Automation Frameworks: pytest

Solid basic computer knowledge includes Computer network(HTTP/TCP/IP), Data structure, basic algorithm.

Experience with kunernetes and docker basic usage.

# Works
1. Ricequant (Permanent)
Sofeware Engineer, Apr 2018 - Present

1. I have prompted and rewritten a new C-S-based MongoDB synchronizer that enables syncing of internal MongoDB data to customers.   Users can specify which database and collection to sync. After careful design, the  synchronizer now achieves the following:
- During full client synchronization, the original database can continue providing services as usual (without a direct increase in workload).
- Customers receive reliable and real-time updates from the original database.
- The company now requires fewer MongoDB instances (from 4 to 1).

2. I have redesigned and rewritten an web service named  "Performance Attribution" for customers. This achieves the following:

- requiring significantly less memory (from 32GB to 8GB)
- performing much faster (with a 70% reduction in runtime in general scenarios).
- Additionally, the service is now more extendable and easier to test.I am also maintaining my company's stock data services

3. I'm also maintaining my company's data services, which includes:
- client side: stock data SDK for customers fetching financial data and market data easily
- server side:
    a. data server
    b. bar-gateway server
    c. index market data real time generator 
    d. user service
    e. license service
    f. etc..
More detailed: https://www.ricequant.com/doc/rqdata/python/

4. I am also working on the following:
- Developing finance services
- Designing RESTful APIs
- Making profile and performance improvements to existing code bases.
- Rewriting some components in rust, it makes these components run 3.5x faster in general.

Tools and Technologies used include: Python 3, Rust, RESTful API design, distributed computing, MongoDB, Jira, Jenkins, Confluence, Redis

2. Dell software (Permanent)
Associate Software Developer, Jun 2016 - Apr 2018

Firstly I'm using python + robotframework to build UAT automation testing for product, and involve in improving testing code performance, which reduces running time from 2hours to 1hour.

Then involve in product development, which mainly using C# and powershell.

Tools & Technologies:
Python, Robotframework, test automation, agile methodologies, C#, AWS, Confluence, Jira, Jenkins

3. Alibaba Group (Internship)
Test Development Engineer, Jun 2015 - Aug 2015

Mainly working on testing security product.

The test process includes: Functional Testing, Performance Testing, Stability Testing

Tools & Technologies:
Python, test automation

# Projects
- Nushell (Apr 2022 - present)
Nushell is an new type of shell, it mainly contains the following feature:
1. multi platform supports, Nushell works with LinuxOS, MacOS, Windows natively.
2. Like powershell, everything is structured data, so we don't need to treated everything as bare string.
3. Provide powerful plugin system, so it's easy to extend nu.
4. It also provides easy to use Nu language.

Currently I'm acting as a core team member, what I have done are:
1. Finishing missing unit tests, which makes user change their code in the future more confidently.
2. solve several bugs in nushell, mainly make nushell works better with external commands.
3. develop a plugin which makes nushell compatible to many binary format, which includes ttf, png, bmp and so on...
4. investigate and develop an nushell lib which empowers background job
5. add signature information when user want to get help on one command, it makes commands much easier to use.
6. Make nushell works better with file redirection.
7. review pull requests from other contributors

All my contributions can be seen here: https://github.com/nushell/nushell/pulls?q=author%3AWindSoilder
