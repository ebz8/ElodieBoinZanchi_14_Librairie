# ebz-react-library

Open-source React components and custom hooks build with TypeScript.

> If you’re new to TypeScript and React, checkout [this handy cheatsheet](https://github.com/sw-yx/react-typescript-cheatsheet/)

## Install

```bash
npm i @elbaz888/ebz-react-library
```

## Components

Here are the available UI components :

### Modal (with 'dialog' element)

To create a new modal instance, import the component and his associated custom hook.

```typescript
import { useModal } from '@elbaz888/ebz-react-library'
import { Modal } from '@elbaz888/ebz-react-library'

// import hooks you need
const { showModal, hideModal, toggleModal } = useModal()
```

and, for example, use the component as :

```typescript
<Modal isOpened={isOpened} onClose={onClose} modalContent="Your content here." />
<button onClick={toggleModal}> Toggle me </button>
```
