## Hopefully something like diep.io

### Technologies:
*   HTML5 Canvas
*   matter.js
*   TypeScript
*   socket.io

### Run
`npm start`

Check out the scripts in package.json for details.
We build the server with `tsc`.
We build the client with webpack and ts-loader so we can use modules. Apparently tsc can't do that for us natively.

### Notes
*   js files are ignored by .gitignore

### TODO
*   Shooting mechanics, Bullet sprites, collision detection.
*   Weapon upgrades, experience
*   Checkered background.
*   Player image + turret that points at mouse.
*   Minimap
*   Use Matter.js.
*   get a linter
*   Fix the `Serializable` interface and how we do serialization. `deserialize()` should probably be a static method that returns a new object. Check for more automated solution for deep serialization.


#### Bugs
*   Sometimes new players not controllable.
*   import socket.io-client cleanly
*   `npm run watchClient` seems to be watching the server.

