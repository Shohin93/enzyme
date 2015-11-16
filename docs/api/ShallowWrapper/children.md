# `.children() => ShallowWrapper`

Returns a new wrapper with all of the children of the node(s) in the current wrapper.


#### Returns

`ShallowWrapper`: A new wrapper that wraps the resulting nodes.



#### Examples

```jsx
const wrapper = shallow(<ToDoList items={items} />);
expect(wrapper.find('ul').children()).to.have.length(items.length);
```

#### Related Methods

- [`.parents() => ShallowWrapper`](parents.md)
- [`.parent() => ShallowWrapper`](parent.md)
- [`.closest(selector) => ShallowWrapper`](closest.md)