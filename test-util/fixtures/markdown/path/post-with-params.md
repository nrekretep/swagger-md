### POST /pets

Creates a new pet

**Parameters**

- body: body (object) - Params for new pet
  - name (string)

#### Response: 201

pet response

**Schema**

- [Pet](#pet)

#### Response: default

unexpected error

**Schema**

- [Error](#error)
