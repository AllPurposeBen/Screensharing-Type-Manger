Work in progres...


Run the app once to register the URL handlers, then you can specify 2 new URI's inplace of the OG `vnc://`:

- `vnc-h://<host>` for high quality sharing
- `vnc-s://<host>` for standard quality sharing

Also included the file `screensharing-types`, which can be sourced in your shell to give some some CLI functions that work similarly:

- `vnc-h <host>`
- `vnc-s <host>`

In both cases, you'll need to grant the app or terminal the TCC permissions for assistive access that it asks for.

TODO:

- Document TCC permissions needed.
    - Create example TCC profile for those.
- Package the app.
    - Look into registering the URL handlers at install.
- Look into what happens if you try to screen share to a host that doesn't offer the 2 types of sharing and handle any breaks to the workflow there.

