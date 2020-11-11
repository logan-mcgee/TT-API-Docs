# Main

All endpoints begin with `/status/`

## `X-Tycoon-Key`
This is the header required for a lot of the requests made to the `/status` endpoints. Needs a valid API key.
For some reason, some of these routes require this, while some don't.


### General Endpoints

#### `/alive`

returns 204 no content, purely designed as a status check.

#### `/charges.json`

returns an array, where the only item is the amount of charges left.

