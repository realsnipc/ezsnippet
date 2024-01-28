## React Snippets

- Function Component - fc

```
export default function react() {
  return (
    <>react</>
  )
}
```

- React Function Component - rfc

```
import React from 'react'

export default function react() {
  return (
    <>react</>
  )
}
```

- React Context API - rca

```
const UserContext = createContext(undefined);
const UserDispatchContext = createContext(undefined);

// A "provider" is used to encapsulate only the
// components that needs the state in this context
function UserProvider({ children }) {

  return (
    <UserContext.Provider value={}>
        {children}
    </UserContext.Provider>
  );
}

export { UserProvider, UserContext };
```
