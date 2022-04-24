# What is this?

Get shadows every time for non-designer.

# Installation

`npm i chupashadows --save`

Then ...

```
import { chupashadows} from 'chupashadows';

chupashadows({
    shadow_type: 'soft',
    padding: false
})
```
## Options

Chupashadows supports 2 options, both of which are optional:

* *shadow_type* - _hard | soft_ (Defaults to soft)
* *padding* - _boolean_ (Defaults to false)