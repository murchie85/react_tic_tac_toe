# REACT LEARNING NOTES 

Using the main react [Tutorial](https://reactjs.org/tutorial/tutorial.html)

1. React is defined in `index.js` 
2. In `src` folder 

### Example Usage 

- The `shopping list` class can now be called using:
- `<ShoppingList name="Mark" />`
  

```javascript
class ShoppingList extends React.Component {
  render() {
    return (
      <div className="shopping-list">
        <h1>Shopping List for {this.props.name}</h1>
        <ul>
          <li>Instagram</li>
          <li>WhatsApp</li>
          <li>Oculus</li>
        </ul>
      </div>
    );
  }
}

```  
  
- Longer way of defining say `<li>` would be to use `createElement()`  method which is bulky and long.  
