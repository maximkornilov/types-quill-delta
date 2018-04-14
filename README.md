# types-quill-delta
Package with typescript type definitions for quill delta project.

This is temporary solution before definitelytyped project will be updated to include separate type definition for quill-delta project.

This package is intentially are not going to be submitted to npm. It is expected that eventually it will be a part of the definitelytyped eco system.

Note: definitions for this projects are base on type definition for [quill](https://www.npmjs.com/package/@types/quill)

## Install
```
yarn add https://github.com/maximkornilov/types-quill-delta/tarball/master -D
```

## Uninstall
```
yarn remove @types/quill-delta
```

## Examples
The following code should work fine:
```
import {default as Delta, DeltaStatic} from "quill-delta"

const delta: DeltaStatic = new Delta();
```
