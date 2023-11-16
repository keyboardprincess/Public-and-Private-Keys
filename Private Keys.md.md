---


---

<h2 id="private-and-public-keys">Private and Public Keys</h2>
<p>A bitcoin wallet contains a collection of key pairs, each consisting of a private key and a public key. The private key (k) is a number, usually picked at random. From the private key, we use elliptic curve multiplication, a one-way cryptographic function, to generate a public key (K). From the public key (K), we use a one-way cryptographic hash function to generate a bitcoin address (A).</p>
<h2 id="private-keys">Private Keys</h2>
<p>A private key is simply a number, picked at random. Ownership and control over the private key is the root of user control over all funds associated with the corresponding bitcoin address. The private key is used to create signatures that are required to spend bitcoins by proving ownership of funds used in a transaction. The private key must remain secret at all times, as revealing it to a third party is equivalent to giving them control over the bitcoins secured by that key.</p>
<p>The private key must also be backed up and protected from accidental loss, since if lost it cannot be recovered and the funds secured by it are forever lost too.</p>
<h2 id="generating-a-private-key-from-a-random-number">Generating a private key from a random number</h2>
<p>The first and most important step in generating keys is to find a secure source of entropy, or randomness. Creating a bitcoin key is essentially the same as “Pick a number between 1 and 2^256“. The exact method you use to pick that number does not matter as long as it Is not predictable or repeatable.</p>
<p>Bitcoin software uses the underlying operating system’s random number generators to produce 256 bits of entropy (randomness). Usually, the OS random number generator is initialized by a human source of randomness, which is why you may be asked to wiggle your mouse around for a few seconds. For the truly paranoid, nothing beats dice, pencil and paper.</p>
<h2 id="how-to-see-all-keys">How to see all keys</h2>
<p>All Bitcoin private keys is simply an integer between number 1 and 115792089237316195423570985008687907852837564279074904382605163141518161494337 or HEX: from 1 to 0xfffffffffffffffffffffffffffffffebaaedce6af48a03bbfd25e8cd0364141. The integer range of valid private keys is governed by the <a href="https://en.bitcoin.it/wiki/Secp256k1" title="Secp256k1">secp256k1</a> ECDSA standard used by Bitcoin.<br>
You can find  <strong>Private key</strong> in WIF (Wallet Import/Export Format) and compressed key.  <strong>Bitcoin addresses</strong> in  <strong>compressed/ uncompressed</strong>  formats,  <strong>SegWit</strong>  (P2SH-P2WPKH) and  **native Segwit (**P2WPKH) addesses start  <em>bc1</em>,  <strong>Pay to script hash</strong> (P2SH) starting with 3;  <strong>legacy Bitcoin Cash</strong> addresses and  <strong>new format.</strong></p>
<p>Check out more contents on <a href="https://github.com/keyboardprincess">KeyboardPrincess</a></p>

