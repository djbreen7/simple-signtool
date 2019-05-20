[simple-signtool](../README.md) > [IRFCTimeStamp](../interfaces/irfctimestamp.md)

# Interface: IRFCTimeStamp

## Hierarchy

**IRFCTimeStamp**

## Index

### Properties

* [digestAlgorithm](irfctimestamp.md#digestalgorithm)
* [url](irfctimestamp.md#url)

---

## Properties

<a id="digestalgorithm"></a>

### `<Optional>` digestAlgorithm

**● digestAlgorithm**: *`undefined` \| "sha256"*

*Defined in sign/signoptions.interface.ts:30*

Used with the `rfcTimeStampUrl.url` option to request a digest algorithm used by the RFC 3161 time stamp server.

___
<a id="url"></a>

###  url

**● url**: *`string`*

*Defined in sign/signoptions.interface.ts:25*

Specifies the RFC 3161 time stamp server's URL.

___
