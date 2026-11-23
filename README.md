# Adena session test

A single static page that checks one thing: can a web page ask the Adena wallet to create a session key on the Onyx test network, list it, and revoke it again?

- Test GNOT on Onyx (`onyx-1`) only.
- No build step, no external scripts, nothing stored.
- The test key is generated in the page and its private half is thrown away, so the session can never be used.

Open the page: https://elangrr.github.io/adena-session-test/
