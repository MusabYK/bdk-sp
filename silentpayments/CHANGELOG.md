# 0.2.0

- Fix bug that allows the creation of silent payment outputs without collecting
  all the eligible input private keys. #63

# 0.1.0

- Functions for encoding and decoding Silent Payment Codes (BIP352).
- Support for deriving Silent Payment script pubkeys and shared secrets.
- Capabilities for scanning transactions to identify Silent Payment outputs.
- Implementation for signing PSBTs that spend Silent Payment outputs.
- Error handling for Silent Payment-related operations.
- Verification against BIP 352 test vectors.
