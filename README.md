# antd4-multiple-lines-select
Select Component showing multiple lines on Ant Design 4

## Usage


```JSX:MultiLineSelect.tsx
import React from 'react';
import { Select } from 'antd';

const MultiLineSelect = () => (
  <Select
    options={optionData}
  />
);
```

```CSS:MultiLineSelect.css
.ant-select-selector {
  white-space: pre-wrap;
  height: fit-content !important;
}

.ant-select-selection-item {
  white-space: pre-wrap;
}

.ant-select-item-option-content {
  white-space: pre-wrap;
}
```
