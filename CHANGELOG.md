## 0.2.1 / 2017-11-04

* [BUGFIX] /chats command send to the sender and not the chat [#10](https://github.com/metalmatze/alertmanager-bot/issues/10)

## 0.2.0 / 2017-10-17

* [BREAKING] Change the `STORE` env var to switch on the store backend instead of path
* [FEATURE] The Bot now ignores its own name as suffix on command in a group chat [[aae2dc5]](https://github.com/metalmatze/alertmanager-bot/commit/aae2dc5c1dae5f865cd697cb649fb757b7efaa6f) 
* [FEATURE] Use libkv as store backend [[6419064]](https://github.com/metalmatze/alertmanager-bot/commit/64190646e71910a10fdcb6e7533dc8a8dc485fec)
* [ENHANCEMENT] Use [dep](https://github.com/golang/dep) to pin dependencies [[b7e085b]](https://github.com/metalmatze/alertmanager-bot/commit/4bfd3f7a2ec559eee712f37ba8e32ca848717905)
* [ENHANCEMENT] Use the Option pattern to change the Bot's default values in `NewBot()`.

## 0.1.0 / 2017-03-31

Initial release.
