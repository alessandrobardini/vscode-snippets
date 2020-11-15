# vscode-snippets
My personal Visual Studio Code snippets.

[Visual Studio Code](https://code.visualstudio.com/) is known for offering a huge number of extensions containing code snippets for almost every programming language. In addition, it's also possible to create personal snippets in a very convenient (and painless) way. This repo contains my own snippets. 

## How to create a custom snippet
Open Visual Studio Code and select **User Snippets** under **File > Preferences** (**Code > Preferences** on macOS).
Select then the language for which the snippets should appear (for example, select **ruby.json** to create snippets for Ruby files) and add a JSON entry corresponding to the new snippet.
For more detailed information, please visit the [Visual Studio Code documentation](https://code.visualstudio.com/docs/editor/userdefinedsnippets#_create-your-own-snippets).

## Snippets
### Typescript React Functional Component With Import

Filename: `Hello.tsx`
```tsx
import React from 'react'

type HelloType = {
  prop: string
}

const Hello: React.FC<HelloType> = ({ prop }) => {
  return (
    <div>
      
    </div>
  )
}

export default Hello
```

### Typescript React Functional Component
Filename: `Hello.tsx`
```tsx
type HelloType = {
  prop: string
}

const Hello: React.FC<HelloType> = ({ prop }) => {
  return (
    <div>
      
    </div>
  )
}
```

### Typescript React Jest Enzyme Test With Import

Filename: `Hello.test.tsx`
```tsx
/* eslint-env jest */
import React from 'react'
import 'jest-enzyme'

describe('Hello', () => {
  it('something', () => {
    
  })
})
```

### Typescript React Jest Enzyme Test

Filename: `Hello.test.tsx`
```tsx
describe('Hello', () => {
  it('something', () => {
    
  })
})
```
