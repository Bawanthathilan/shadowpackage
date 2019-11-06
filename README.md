# what is this?

get perfect shadows every time for the non-designer.

# installation
`npm i shadowpackage --save`

Then ...

```
import { shadowpackage } from 'shadowpackage';

shadowpackage({
    shadow_type: 'soft';
    padding: false
});
```

## options
Shadowpackage supports 2 options, both of which are optional
* *shadow_type* - _hard / soft_ (Defaults to soft)
* *padding* - _boolean_ (Defaults to false)