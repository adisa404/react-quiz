# init

npm i

npm run test

# command pro module

npm run test:module1

# kad smo u najnizoj komponenti

```js
onClick={this.props.handleResetClick}>
```

handleResetClick samo poziva metodu koja je u parentu definisana kao 'handler'

ovo je bilo too advanded za njih

kod koji njima odgovara

```js

handleResetClick() {
    this.props.resetClickHandler();
  }
  render() {
    return (
      <div>
        <p>Thanks for playing!</p>
        <a href="" onClick={this.handleResetClick.bind(this)}>
          Reset Quiz
        </a>
      </div>
    );
  }
```
