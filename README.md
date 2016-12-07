# CS585FP
Final Project - Selenium IDE
Project: Selenium IDE

Selenium Ide is an integrated development environment, it helps to easily record and generate test scripts. This web generating tests tool is easy to install and use, it is used for automating web based process, so instead of checking the running of links of the web page manually , we can use this tool to automatically generate the checking process.  However, its a Firefox adds on. Also, this forgoing tool allow you to debug and set breakpoints. In addition, it could automatically record and edited manually providing auto-completion support and the ability to move commands around quickly. Moreover, Scripts can be recorded in Selenese, a which will provide commands for performing actions in a browser (click a link, select an option), and for retrieving data from the resulting pages. Furthermore, this tool is used with web application and it can be exported to other programming languages such as: Java, C#, or Ruby. 

In this project I had to download and use Firefox browser because this too is a Firefox adds on. I also downloaded Fire bugs which is a Firefox add on tool, using this tool we can edit debug, and monitor the CSS, HTML, and JavaScript in the web page. The Firefox browser help u to view the html source code but using firebug we can actually identify the elements of the page. After that, I download and install the selenium ide and I generate simple user interaction unit tests, including verify and assert tests. It simply will open the https://uk.yahoo.com/ and search for the the Cal poly Pomona website, and from there going to the blackboard and download one of the lectures. Moreover, I did show simple run script with confirmation, alert, and the console. 

Selenuim IDE provides tools menu where you easily load or create new test classes. It has menu bar and tool bar that is very easy to use. One of the great feature is recording, we can easily recode a test case from user interaction with the website and the aforementioned tool will automatically insert commands into the test cases based on the action the user did. Another point is verification and asserting, we can check the properties of a web page using assert and verify commands. For example, we can verify a paragraph or a heading using verifyTextPresent command with the text itself as a parameter. There are types of commands in Selenium, Actions, Accessors, and Assertions. The Action Commands are those in which they manipulate the state of the application. The Accessor Commands examine the state of the application and store the results in variables. Finally, Assertions verify that the state of the application conforms to what is expected. 
We can verify the page elements text, image is it in the page or in specific position in the page using verify and assert. The verify command will verify the condition and if its not match, it will give error message but will continue executing to next commands. while in assert command, if condition does not match then it will stop execution.
 
 The commands I used in the project is:
 
1-	Open:  This is will open the desired URL
2-	Type: Typing a text
3-	Click: perform a click
4-	 ClickAndWait: perform a click and waits for a new page to load 
5-	verifyTitle: verify an expected page title
6-	VerifyTextPresent: verify expected text is somewhere on the page 
7-	assertTitle: verify an expected page table 
8-	selectFrame: this command will perform some action on element inside the iframe of the page
9-	runscript: to run the javascript 
10-	verifyElementPresent : verify the existence of an element in the page. 
