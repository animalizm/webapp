

```jsx:component:clock
// file: Clock.md
 const [date, setDate] = useState(new Date());
 useEffect(() => {
  var timerID = setInterval( () => setDate(new Date()), 1000 );
  return function cleanup() {
      clearInterval(timerID);
    };
 });
return (
  <div>
	<h1>Hello, world!</h1>
	<h2>It is {date.toLocaleTimeString()}.</h2>
  </div>
); 
```






