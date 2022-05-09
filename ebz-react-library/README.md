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
```

and use it in a functionnal component :

```typescript
// import hooks you need before the render
const { showModal, hideModal, toggleModal } = useModal()

<button onClick={toggleModal}> Toggle me </button>
<Modal isOpened={isOpened} onClose={onClose} modalContent="Your content here." />
```

> Full documentation and demo in [Storybook doc](https://ebz-react-library.netlify.app/)
