







```
jsx:
import styled from 'https://cdn.skypack.com/styled-components/';
import confetti from 'https://cdn.skypack.dev/canvas-confetti';

const Btn = styled.button` 
	color: white; 
	background: red; 
	:hover { 
		background: blue;
	} 
	:active {
		background: orange; 
	}
`;

<Btn onClick={()=>confetti()}> This is a red button </Btn>
```


