# Bitcoin Cash Protocol

-   [Style Guide](/style-guide)
-   [Contributors](/contributors)
-   [Target Audience](/target-audience)
-   [Project History](/project-history)
-   Protocol
    -   Blockchain
	    -   [Hash](/protocol/blockchain/hash)
	    -   [Transaction](/protocol/blockchain/transaction)
		    -   [Unlocking Script](/protocol/blockchain/transaction/unlocking-script)
		    -   [Locking Script](/protocol/blockchain/transaction/locking-script)
	    -   [Block](/protocol/blockchain/block)
		    -   [Header](/protocol/blockchain/block/block-header)
		    -   [Merkle Tree](/protocol/blockchain/block/merkle-tree)
		    -   [Transaction Ordering](/protocol/blockchain/block/transaction-ordering)
	    -   [Script](/protocol/blockchain/script)
		    -   Opcodes
			       ...
	    -   Transaction Validation
		    -   Block Level Validation Rules
		    -   Network Level Validation Rules
			    -   Standardness Rules
				    -   Custom / Non Standard
	    -   Cryptography
		    -   Secp256k1
			    -   Public Key
				    -   Compressed
				    -   Uncompressed
			    -   Private Key
		    -   Signatures
			    -   ECDSA
			    -   Schnorr
			    -   DER Encoding
				    -   (OpenSSL History?)
			    -   N-of-M Multisig Signatures
	    -   Bitcoin Address
		    -   Pay To Public Key
			-   Pay To Public Key Hash
		    -   Pay To Script Hash
		    -   Encodings
			    -   Legacy (Base 58)
			    -   Bech32
			    -   Cash Address
	    -   Proof of Work
		    -   Difficulty Adjustment Algorithm
			    -   Legacy DAA
			    -   Emergency DAA
			    -   BCH Adaptive DAA
	-   Mining
		-   Stratum Protocol
	    -   Mining Pools
	-   Forks
	    -   Bip-16
		-   [Bip-34](/protocol/forks/bip-0034)
		-   [Bip-37](/protocol/forks/bip-0037)
		-   [Bip-64](/protocol/forks/bip-0064)
		-   Bip-65
		-   Bip-66
		-   Bip-68
		-   Bip-112
		-   Bip-113
		-   [Bip-157](/protocol/forks/bip-0157)
		-   [Bip-158](/protocol/forks/bip-0158)
		-   [Bip-159](/protocol/forks/bip-0159)
		-   BCH UAHF (BUIP-55)
		-   HF20171113
		-   HF20180515
		-   HF20181115
		-   HF20190515
		-   HF20191115
	-   Peer-to-Peer Network
        - [Messages](/protocol/network/messages)
            - *Announcements*
              - filteradd
              - filterclear
              - filterload
              - inv
	        - *Requests*
              - feefilter
              - getaddr
              - getblocks
              - getdata
              - getheaders
              - [Ping](/protocol/network/messages/ping)
              - sendheaders
              - [Handshake: Version](/protocol/network/messages/version)
            - *Responses*
              - addr
              - block
              - headers
              - notfound
              - merkleblock
              - [Pong](/protocol/network/messages/pong)
              - reject
              - tx
              - [Handshake: Acknowledge Version](/protocol/network/messages/verack)
            - *Non-Standard*
              - sendcmpct
              - get_xthin
              - xthinblock
              - thinblock
              - get_xblocktx
              - xblocktx
        - [Node Handshake](/protocol/network/node-handshake)
    -   Simple Payment Verification (SPV)
	    -   Bloom Filters
    -   Simple Ledger Protocol
    -   Cash Address
    -   Miscellaneous
	    - “Bitcoin Sign Message”
	    - [Endian](/protocol/misc/endian)
		    - [Little](/protocol/misc/endian/little)
		    - [Big](/protocol/misc/endian/big)
   -   History
	   - Bips
	   - Protocol Version