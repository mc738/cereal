# Cereal

`cereal` is a simple library/protocol for communitcating with arduinos via serial on `*nix`  computers.

In time it might be expanded to handle other operating systems and use cases.

`cereal` is designed to be for support a few modes:

* Line mode
	* Read/write data by line
* Frame mode
	* Read/write data by fixed sized frames
* Operations
	* Read/write data by specific operations

The library starts a thread to handle serial communitications which exposes channels for data IO.

The library is meant to be relevatively simple and a bridge.
As such the library is not designed (*yet*) for millisecond accrutary needed for some usecases. 
