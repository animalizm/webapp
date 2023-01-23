---
defines-react-components: true 
---


```jsx:component:counter
// file: Counter.md
const [count, setCount] = useState(0)
return (
<div>
  <p>You clicked me {count} times!!!</p>
  <button onClick={() => setCount(count + 1)}>
	{props.source}
  </button>
</div>
)
```






