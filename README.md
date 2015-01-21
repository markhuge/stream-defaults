# stream-defaults
Apply default keys/values to objects as they pass through your streams

## Install

`npm install stream-defaults`

## Usage

```JS
var defaults = require('stream-defaults'),
    opts     = { from: "support@mycompany.com", template: "default_template" }

fetchMsgFromQueue().pipe(defaults(opts)).pipe(sendMail);
```

