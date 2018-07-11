# testing-goat
Test-Driven Development with Python's code

[url](https://www.safaribooksonline.com/library/view/test-driven-development-with/9781491958698/)

[amazon](https://www.amazon.co.jp/dp/B074HXXXLS/ref=dp-kindle-redirect?_encoding=UTF8&btkr=1)

## Prerequisites and Assumptions

[url](https://www.safaribooksonline.com/library/view/test-driven-development-with/9781491958698/preface02.html#firefox_gecko)

- python3
- a little javascript
- with system installed firefox and Geckodriver
- original process (ubuntu-cui on virtual box) 
    - install and run xvdf (https://web-dev.hatenablog.com/entry/linux/ubuntu/install-firefox-xvfb)
    - export DISPLAY=:99

## Chapter 1. Getting Django Set Up Using a Functional Test
[url](https://www.safaribooksonline.com/library/view/test-driven-development-with/9781491958698/ch01.html)

- update .gitignore
- run tests with selenium and firefox
- django command runserver for executing web server

## Chapter 2. Extending Our Functional Test Using the unittest Module
[url](https://www.safaribooksonline.com/library/view/test-driven-development-with/9781491958698/ch02.html#chapter_02_unittest)

- building a to-do list sites
    - it is very simple - just a list of text
    - There's no reason to be limited to just "to-do"
- FTs(functional tests) should have a human-readable story that we can follow
- unittest module give us various assertion methods and setUp/tearDown like try/finally sentense
- Firstly, we make User Stroy using comments that accompany the test code
    
## Chapter 3. Testing a Simple Home Page with Unit Tests
[url](https://www.safaribooksonline.com/library/view/test-driven-development-with/9781491958698/ch03.html)
