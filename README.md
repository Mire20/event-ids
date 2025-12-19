# Event IDs
A script to generate all the event provider/id/message bundles from a database as `GO`, `CSV`, `JSON` files. Roughly about *51600* for a Windows 10 system.

Based on the `welm_combined.db` from [evtx-data](https://github.com/Velocidex/evtx-data/tree/master/welm) by [Velocidex](https://github.com/Velocidex).

## Usage
```console
$ ./generate.py events.db
```

## License
Released under the [MIT License](LICENSE.md).