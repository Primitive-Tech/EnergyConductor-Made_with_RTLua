
### Web Client Functions

- `webClient:new(adress)`:
  - Lua: Initializes a new HTTP web client instance.

- `webClient:newFtp(adress, user, pw)`:
  - Lua: Initializes a new FTP web client instance with the given address, username, and password.

- `webClient:get(file)`:
  - Lua: Performs a GET request using the web client instance. Returns the response content and an optional HTTP instance.

- `webClient:patch(file)`:
  - Lua: Performs an upload request using the web client instance and the specified file.

### Socket Communication Functions

- `DirectConnect()`:
  - Lua: Establishes a direct socket connection to a specified host and port.

- `listener()`:
  - Lua: Binds and listens to a specified host and port, waiting for incoming connections. Prints received data from the connected client.

LICENSE).
