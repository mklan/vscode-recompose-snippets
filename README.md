# VS Code Recompose snippets

[![Version](https://vsmarketplacebadge.apphb.com/version/mklan.recompose-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=mklan.recompose-snippets)
[![Install](https://vsmarketplacebadge.apphb.com/installs/mklan.recompose-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=mklan.recompose-snippets)
[![Ratings](https://vsmarketplacebadge.apphb.com/rating-short/mklan.recompose-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=mklan.recompose-snippets)

This extension provides [Recompose](https://github.com/acdlite/recompose/) snippets for [Vs Code](https://code.visualstudio.com/)

Direct link to marketplace [Recompose Snippets](https://marketplace.visualstudio.com/items?itemName=mklan.recompose-snippets)

## Snippets

### `rec→`

![rec preview](https://github.com/mklan/vscode-recompose-snippets/blob/master/previews/recompose.gif?raw=true)


```javascript
  import React from 'react':
  import { compose } from 'recompose';
  
  const ${1:Component} = ({ ${2:someProp} }) => (
    	    $0
	);
			
  export default compose(
  
  )(${1:Component});
```

### `withH→`

![withH preview](https://github.com/mklan/vscode-recompose-snippets/blob/master/previews/withHandlers.gif?raw=true)

```javascript
  withHandlers({
    ${1:yourHandler}: ({ ${2:someProp} }) => (${3:val}) => {
    	$0  
    },
  }),
```

### `rech→`

![rech preview](https://github.com/mklan/vscode-recompose-snippets/blob/master/previews/handler.gif?raw=true)

```javascript
  ${1:yourHandler}: ({ ${2:someProp} }) => (${3:val}) => {
  	$0  
  },
```

### `withS→`

![withS preview](https://github.com/mklan/vscode-recompose-snippets/blob/master/previews/withState.gif?raw=true)

```javascript
  withState('${1:prop}', '${2:setProp}'$0),
```

## Supported languages (file extensions)

- JavaScript (.js)
- JavaScript React (.jsx)
- TypeScript (.ts)
- TypeScript React (.tsx)
