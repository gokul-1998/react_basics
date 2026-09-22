## 1) if we use plain html, we need to do lot of manual code.



## 2) react has component based architecture.

## 3) if we use normal html , it will download entire code from the server.or entire page from the server, but react will only load that changed component.this is called Virtual DOM

## 4) what is DOM?
    - Document object model
    - DOM is a tree structure that represents the html document.

    html
        head
            title
        body
            h1
            p

5) is react a framework or library?
    - library 

6) what is a framework?
    - common structure
    - rules
    - guidelines
    - Example: 
        - Angular
        - Vue
        - Next.js

7) UI/UX
    - User interface / User Experience
    - front end development
    - example: 
        - attractive
        - responsive
        - user friendly

8) what is SPA?
    - Single Page Application
    - it means there is only one html page, and we are dynamically loading the content of the page.
    - example: 
        - gmail
        - facebook
        - instagram

9) what is component?
    - component is a reusable piece of code that can be used to build a user interface.
    - example: 
        - header
        - footer
        - sidebar
        - button
        - input
        - card
        - navbar


10) what is spa in web, short and sweet

**SPA (Single Page Application)** is a web application where the browser loads **one main HTML page**, and the content changes dynamically without fully reloading the page.

**Example:** React, Vue, and Angular apps.

👉 **Normal website:** Click → entire page reloads
👉 **SPA:** Click → only required content updates

**Popular example:** Gmail — navigating between Inbox, Sent, etc. happens without a full page reload.

## 11) give code for prime number

Here’s a simple Python program to check whether a number is prime:

```python
n = int(input("Enter a number: "))

if n < 2:
    print("Not Prime")
else:
    for i in range(2, n):
        if n % i == 0:
            print("Not Prime")
            break
    else:
        print("Prime")
```

**Example:**

```text
Enter a number: 7
Prime
```



12) what is a reusable component?
    - write once use it every where

13) what is full form of html?
    - hyper text markup language

14) lets learn about extensions
    - mp3 - audio
    - mp4 - video
    - jgp - image
    - css - cascading style sheet
    - js -> java script
    - py - python
    - md  - mark down
    - png - image
    - jsx - javascript xml -> js + html

15) what is .jsx?
    - It's like HTML inside JavaScript.
    - HTML → structure
    - JS → logic
    - JSX → structure + logic together.