# Practical TDD with Javascript

Learning Test-Driven Development with JavaScript.

### TDD work flow

![TDD work flow](https://github.com/gedhean/practical-javascript-with-tdd/blob/master/tdd-work-flow.png)

### Thinking TDD

"It should do that when this"

- what should the method do?
- what it receive as argument?
- what it return?
- when it run?

```javascript
it('should return 4 when sum(2,2)', () => {
  expect(sum(2,2)).to.equal(4)
}
```

### Test Types

##### Unit Test

Simple and fast automated test to check the isolated behaivor of unique methods.

##### Integration Test

Test the behaivor of components (unit tests) working together.

##### Aceptation Test (E2E)

Test the external quality of the product and maybe usability.

![Test pyramid](https://github.com/gedhean/practical-javascript-with-tdd/blob/master/testing-pyramid.jpg)

### Speis, Stubs, Mocks

[See](http://walde.co/2017/02/05/testes-e-javascript-diferenca-entre-fake-spy-stub-e-mock/)

