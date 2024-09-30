## API Report File for "@backstage/plugin-org-react"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts
import { GroupEntity } from '@backstage/catalog-model';
import { default as React_2 } from 'react';

// @public (undocumented)
export const GroupListPicker: (
  props: GroupListPickerProps,
) => React_2.JSX.Element;

// @public
export type GroupListPickerProps = {
  defaultValue?: string;
  placeholder?: string;
  groupTypes?: Array<string>;
  onChange: (value: GroupEntity | undefined) => void;
};

// Warnings were encountered during analysis:
//
// src/components/GroupListPicker/GroupListPicker.d.ts:15:22 - (ae-undocumented) Missing documentation for "GroupListPicker".

// (No @packageDocumentation comment for this package)
```