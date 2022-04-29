# Instructions  

Create a P2SH script you've made on testnet + the scriptSig data that will spend it. 

Fill in the information about your transactions and copy any bitcoin-cli logs into the logs.txt file.

  ## Steps
  1. Write a non-standard script (locking and unlocking scripts which are NOT P2PK, P2PKH, or P2MS)
  2. Convert the scriptPubKey (locking script) into a P2SH
  3. Lock coins to your P2SH address
  4. Unlock the coins from your P2SH address by spending them back to yourself

## Fill in the following questions about your Transactions and non-standard Script

1. Write out your non-standard script with opcodes as it will be evaluated on the stack, scriptSig then scriptPubKey:

e.g. a P2PK looks like this: 

scriptPubKey = \<pubkey\> OP_CHECKSIG

scriptSig = \<signature\> 

How it's evaluated on the stack = \<signature\> \<pubkey\> OP_CHECKSIG

2. P2SH scriptPubKey (locking script) in Hex: 

3. P2SH scriptSig (unlocking script) in Hex:

4. P2SH scriptPubKey encoded as a base58 testnet address:

(Hint: the hash of the hex_string != the hash of the bytes, make sure you're hashing at the byte level)

5. TXID of transaction spending TO your P2SH on testnet: 

6. TXID of transaction spending FROM your P2SH on testnet:

7. Raw Unsigned Transaction of TX spending TO your P2SH:

8. Raw Unsigned Transaction of TX spending FROM your P2SH:

9. Raw SIGNED Transaction of TX spending TO your P2SH:

10. Raw SIGNED Transaction of TX spending FROM your P2SH:

