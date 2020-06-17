## Type examples 

Common and not so common React type examples. 

***If the example does not have an import then it is a general html type.***

These will be updated periodically. If I have to look up the type, it will endup here.

### On focus event
Input - can be any focusable html element

```
import { FocusEvent } from 'react';
const onFocus = (event : FocusEvent<HTMLInputElement>): void => {};
```
### On change event

Input - can be any onChangable?... html element
```
import { ChangeEvent } from 'react';
const onChange = (event: ChangeEvent<HTMLInputElement>): void => {}
```
### Keyboard event

```const onKeyPress = (e: KeyboardEvent): void => {};```

### Mouse click event

```const onClick = (e: MouseEvent): void => {}```

### useRef

Input - can be any react node

```const ref = useRef<HTMLInputElement>(null);```

