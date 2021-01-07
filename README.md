# Amper-Sourcecode

{
  "scriptPubKey": "OP_RETURN 534c5000 01 47454e45534953 414e5443 416d706572 68747470733a2f2f616d7065726e6574776f726b2e38622e696f2f c1df5d2b3496568adc75a346c0297d1dbe7ca8b563b594b6624473733cc93686 08 02 002386f26fc10000",
  "slpData": {
    "graph": [
      {
        "_id": "5ff6d142b58ce4ebb5b986c7",
        "tokenDetails": {
          "tokenIdHex": "2d7869f5336f51ad920e26e675d29dcde62fa8d746eb8063ceff33275781a5d6"
        },
        "graphTxn": {
          "txid": "2d7869f5336f51ad920e26e675d29dcde62fa8d746eb8063ceff33275781a5d6",
          "details": {
            "decimals": 8,
            "tokenIdHex": "2d7869f5336f51ad920e26e675d29dcde62fa8d746eb8063ceff33275781a5d6",
            "timestamp": null,
            "timestamp_unix": null,
            "transactionType": "GENESIS",
            "versionType": 1,
            "documentUri": "https://ampernetwork.8b.io/",
            "documentSha256Hex": "c1df5d2b3496568adc75a346c0297d1dbe7ca8b563b594b6624473733cc93686",
            "symbol": "ANTC",
            "name": "Amper",
            "batonVout": 2,
            "containsBaton": true,
            "genesisOrMintQuantity": "100000000",
            "sendOutputs": null
          },
          "outputs": [
            {
              "slpAmount": "100000000",
              "address": "simpleledger:qrffu5cmxmrs8h2c39lghxqg7m5rf5w96520q94w7k",
              "vout": 1,
              "bchSatoshis": 546,
              "spendTxid": "e24aae8e1649b4f0e6d7c37e32c64b6c33945edafd7ea0a8998a4a93df4394b0",
              "status": "SPENT_SAME_TOKEN",
              "invalidReason": null
            },
            {
              "slpAmount": "0",
              "address": "simpleledger:qrffu5cmxmrs8h2c39lghxqg7m5rf5w96520q94w7k",
              "vout": 2,
              "bchSatoshis": 546,
              "spendTxid": null,
              "status": "BATON_UNSPENT",
              "invalidReason": null
            }
          ],
          "inputs": [],
          "_blockHash": "AAAAAAAAAAAFFjjX5+a0MrM/Yo/4Bt2284huq70M7yA=",
          "_pruneHeight": null
        }
      }
    ],
    "slp": {
      "valid": true,
      "detail": {
        "decimals": 8,
        "tokenIdHex": "2d7869f5336f51ad920e26e675d29dcde62fa8d746eb8063ceff33275781a5d6",
        "transactionType": "GENESIS",
        "versionType": 1,
        "documentUri": "https://ampernetwork.8b.io/",
        "documentSha256Hex": "c1df5d2b3496568adc75a346c0297d1dbe7ca8b563b594b6624473733cc93686",
        "symbol": "ANTC",
        "name": "Amper",
        "txnBatonVout": 2,
        "txnContainsBaton": true,
        "outputs": [
          {
            "address": "simpleledger:qrffu5cmxmrs8h2c39lghxqg7m5rf5w96520q94w7k",
            "amount": "100000000"
          }
        ]
      },
      "invalidReason": null,
      "schema_version": 79
    }
  }
}
