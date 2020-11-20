# Routing 

1. Do child components have direct access to props/state from the parent? yes.

2. When a component “wraps” another component, how does the child component’s output get rendered?
- <Main> <Content /> </Main>

3. Can a component, such as <Content />, which is a child also be used as a standalone component elsewhere in the application?
- Yes.
4. What trick can a parent use to share all props with it’s children
- this.props.children(doSomething);

## Vocabulary Terms:

- props.children: This is how we pass props from a parent component to all its children components.

- Composition: is a natural pattern of the component model. It's how we build components from other components, of varying complexity and specialization through props. Depending on how generalized these components are, they can be used in building many other components. [Source](https://dev.to/bouhm/thinking-in-react-component-composition-fp5#:~:text=In%20React%2C%20composition%20is%20a,in%20building%20many%20other%20components.)