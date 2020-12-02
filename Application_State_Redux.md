# Application State with Redux 

1. What are the advantages of storing tokens in “Cookies” vs “Local Storage”
- Basically because it is pure javascript, using local storage is convenient. The Con is that a hacker can use javascript and steal the access token from local storage. Cookies on the other hand, cannot be accessed using javascript and it is automatically sent with every http request. [Source](https://dev.to/cotter/localstorage-vs-cookies-all-you-need-to-know-about-storing-jwt-tokens-securely-in-the-front-end-15id)

2. Explain 3rd party cookies.
- Third-party cookies are those created by domains other than the one the user is visiting at the time, and are mainly used for tracking and online-advertising purposes. They also allow website owners to provide certain services, such as live chats.[Source](https://clearcode.cc/blog/difference-between-first-party-third-party-cookies/#:~:text=Third%2Dparty%20cookies%20are%20those,services%2C%20such%20as%20live%20chats.)

3. How do pixel tags work?
- Marketing pixels, aka tracking pixels, are essentially these tiny snippets of code that allow you to gather information about visitors on a website—how they browse, what type of ads they click on, etc. This behavior data helps you, as a marketer, send the user paid ads that are likely to be most interesting to them.
[Source](https://www.digitalmarketer.com/blog/what-is-tracking-pixel/)


## Vocabulary Terms: 

- Cookies: is a small piece of data stored on the user's computer by the web browser while browsing a website. Cookies were designed to be a reliable mechanism for websites to remember stateful information (such as items added in the shopping cart in an online store) or to record the user's browsing activity (including clicking particular buttons, logging in, or recording which pages were visited in the past)[Source](https://en.wikipedia.org/wiki/HTTP_cookie)

- Authorization: is a security mechanism to determine access levels or user/client privileges related to system resources including files, services, computer programs, data and application features. [Source](https://economictimes.indiatimes.com/definition/authorization#:~:text=Definition%3A%20Authorization%20is%20a%20security,programs%2C%20data%20and%20application%20features.&text=Key%20factors%20contain%20user%20type,and%20related%20actions%20and%20roles.)

- Access Control: is the act of ensuring that an authenticated user accesses only what they are authorized to and no more. ... The issues surrounding authorization are explored in detail as well as both database and object-oriented implementation strategies.[Source](http://www.agiledata.org/essays/accessControl.html#:~:text=Security%20access%20control%20is%20the,authorized%20to%20and%20no%20more.&text=The%20issues%20surrounding%20authorization%20are,and%20object%2Doriented%20implementation%20strategies.)

- Conditional Rendering:  it's generally used in the following processes: Showing/hiding an element: Like a button. [Source](https://medium.com/better-programming/4-ways-to-conditionally-render-in-react-3785fb5e5013#:~:text=If%20you're%20a%20React,an%20element%3A%20Like%20a%20button.)