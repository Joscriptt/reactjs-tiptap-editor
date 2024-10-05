---
description: Attachment
---

# Attachment

Attachment is a node extension that allows you to add an Attachment to your editor.

## Usage

```tsx
import { Attachment } from 'reactjs-tiptap-editor'; // [!code ++]

const extensions = [
  ...,
  // Import Extensions Here
  Attachment.configure({// [!code ++]
    upload: (file: any) => {// [!code ++]
      // upload file to server return url
    },// [!code ++]
  }),// [!code ++]
];
```