HTML template for offline printing a multi-coin crypto wallet.

Cut-and-paste the addresses & keys. QR codes are automatically generated.

Usage:
1) Download HTML and JS onto a secure, single-use computer to be used for
offline wallet generation.
2) Go offline. Generate your wallets (with other tools).
3) Open the HTML. Cut and paste the addresses & keys in. QR codes are
automatically generated.
4) Print. Nuke the computer & printer.

Advanced:
Edit the HTML directly to add/remove currencies from the template.

Alternative:
BIP-0032 & BIP0044 attempt to standardize a multi-coin wallet based on a
single seed. However at the time of writing there is not yet consensus on how
to derive keys for some coins. For example, there is debate over the BIP-32 path
for Ethereum, and different clients that claim to be BIP-44 compatible use
different paths! This makes me wary of cross-client compatibility, and could
make retrieving coins from cold storage in many years challenging.
