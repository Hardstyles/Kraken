Kraken is a PoS-based cryptocurrency.

Krakencoin is dependent upon libsecp256k1 by sipa, the sources for which can be found here: https://github.com/bitcoin/secp256k1

Port: 14117 RPC Port: 14116

Magic Bytes: 0x4e 0x4d 0x4c 0x43

Krakencoin includes an Address Index feature, based on the address index API (searchrawtransactions RPC command) implemented in Bitcoin Core but modified implementation to work with the KC codebase (PoS coins maintain a txindex by default for instance).

Initialize the Address Index By Running with -reindexaddr Command Line Argument. It may take 10-15 minutes to build the initial index.
