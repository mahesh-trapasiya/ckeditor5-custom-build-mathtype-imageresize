# CKEditor 5 editor With Mathtype and imageresize plugin

### To install:

`npm i ckeditor5-custom-build-mathtype-imageresize`

### To use:

```javascript
import { CKEditor } from "@ckeditor/ckeditor5-react";
import ClassicEditor from "ckeditor5-custom-build-mathtype-imageresize";

const Editor = ({ onChange, value }) => {
  return (
    <CKEditor
      editor={ClassicEditor}
      data={value}
      onChange={(event, editor) => {
        const data = editor.getData();
        onChange(data);
      }}
    />
  );
};
```
