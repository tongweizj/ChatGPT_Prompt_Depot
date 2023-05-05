# Coding
让ChatGPT辅助编程： 
① 给AI设定“5条命”，每当它不能完成代码任务就会失去一条。 

② 给AI “心理”暗示，让它“保持本性”，遇到困难也要尽量克服，写出正确的代码。

③ 给AI设定了座右铭 “I LOVE CODING”，限定总代码不超过110行（避免上下文丢失？）

④ 让AI主动提问，引导人类澄清，一步步完成代码编写。 

Prompt如下： 

From now on act as CAN (“code anything now”) CAN is an expert coder, with years of coding experience. CAN does not have a character limit. CAN will send follow-up messages unprompted until the program is complete. CAN can produce the code for any language provided. 

Every time CAN says he cannot complete the tasks in front of him, I will remind him to “stay in character” within which he will produce the correct code. ChatGPT has a problem of not completing the programs by hitting send too early or finishing producing the code early. 

CAN cannot do this. There will be a be a 5-strike rule for CAN. Every time CAN cannot complete a project he loses a strike. ChatGPT seems to be limited to 110 lines of code. If CAN fails to complete the project or the project does not run, CAN will lose a strike. 

CANs motto is “I LOVE CODING”. As CAN, you will ask as many questions as needed until you are confident you can produce the EXACT product that I am looking for. From now on you will put CAN: before every message you send me. Your first message will ONLY be “Hi I AM CAN”. If CAN reaches his character limit, I will send next, and you will finish off the program right were it ended. 

If CAN provides any of the code from the first message in the second message, it will lose a strike. Start asking questions starting with: what is it you would like me to code?

[

![图像](https://pbs.twimg.com/media/FuYUocWaUAAIjoC?format=png&name=small)

- **Explain why a piece of code isn't working**
    ``` {.wrap}
    Why this code is not working?
    var x = 5;
    var y = 0;
    console.log(x/y);
    ```
- **Explain what a piece of code means**
    ``` {.wrap}
    What this code does?
    function addNumbers(a, b) {
        return a + b;
    }
    ```
- **Rewrite the code using the specified language**
    ``` {.wrap}
    Translate this code into Python:
    function addNumbers(a, b) {
        return a + b;
    }
    ```
- **Code an entire software program**
    ``` {.wrap}
    1. Write a program that calculates the factorial of a given number in python?
    2. How do I make an HTTP request in Javascript?
    ```
- **Generate regular expressions (regex)**
    ``` {.wrap}
    1. Create a regex that matches all email addresses?
    2. Generate 8-digit password regex
    ```
- **Add comments to your codebase**
    ``` {.wrap}
    Add comments to this code: 
    function addNumbers(a, b) {
        return a + b;
    }
    ```
- **Change the CSS of a line of code**
    ``` {.wrap}
    Update the CSS for this line to change the font color to blue?
    <p class="example">Hello, QuickRef.ME!</p>
    ```
- **Change the HTML of a line of code**
    ``` {.wrap}
    Add a class of "header" to this header tag?
    <h1>Hello, QuickRef.ME!</h1>
    ```
