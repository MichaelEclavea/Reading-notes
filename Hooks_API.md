# Hooks API 

1. Why do we not need more .html pages in a multi-page React app?
- Because components let you render different elements or basically different pages onto one canvas, which is the one html page. 

2. If we wanted a component to show up on every page, where would we put it and why?
Outside the <BrowserRouter/>
Inside the <BrowserRouter />, outside a <Route />
Inside a <Route />
- My understanding of the BrowserRouter, was to lay whatever component tag outside the Switch tags.

3. What does props.children contain?
- Whatever that was passed through the component opening and closing tag

## Vocabulary Terms

- Composition:  is a natural pattern of the component model. It's how we build components from other components, of varying complexity and specialization through props. [Source](https://dev.to/bouhm/thinking-in-react-component-composition-fp5)

- Children/Child Components: children . Children allow you to pass components as data to other components, just like any other prop you use. The special thing about children is that React provides support through its ReactElement API and JSX. XML children translate perfectly to React children! [Source](https://buildwithreact.com/article/component-children#:~:text=children%20.,translate%20perfectly%20to%20React%20children!)

- Hash Routing: The hash router component uses window.location.hash (the hash portion of the url) to remember the changes in the browsers history stack. [Source](https://subscription.packtpub.com/book/web_development/9781789532555/5/ch05lvl1sec33/-hashrouter-component)

- Link Routing: provides the <Link> and <NavLink> components, which allow you to navigate to different routes defined in the application. These navigation components can be thought of as being like anchor links on the page that allow you to navigate to other pages in the site. [Source](https://www.codementor.io/@packt/using-the-link-and-navlink-components-to-navigate-to-a-route-rieqipp42)