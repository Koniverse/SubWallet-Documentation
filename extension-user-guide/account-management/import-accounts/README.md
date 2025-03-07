---
description: Import your existing accounts onto SubWallet using backup information.
---

# Import accounts

### Supported import methods

You can import your existing accounts onto SubWallet via one of the following methods: seed phrase, JSON file, private key, or QR code.

<table><thead><tr><th width="189">Account type</th><th width="105" data-type="checkbox">Seed phrase</th><th data-type="checkbox">JSON file</th><th data-type="checkbox">Private key</th><th data-type="checkbox">QR code</th></tr></thead><tbody><tr><td><strong>Unified account</strong></td><td>true</td><td>true</td><td>false</td><td>false</td></tr><tr><td><strong>Substrate account</strong></td><td>false</td><td>true</td><td>false</td><td>true</td></tr><tr><td><strong>EVM account</strong></td><td>false</td><td>true</td><td>true</td><td>true</td></tr><tr><td><strong>TON account</strong></td><td>true</td><td>true</td><td>true</td><td>false</td></tr><tr><td><strong>Cardano account</strong></td><td>false</td><td>true</td><td>false</td><td>false</td></tr><tr><td><strong>Ledger account</strong>*</td><td>false</td><td>true</td><td>false</td><td>false</td></tr><tr><td><strong>QR-signer account</strong>*</td><td>false</td><td>true</td><td>false</td><td>false</td></tr></tbody></table>

_(\*): With Ledger & QR-signer accounts, you will still need to perform transactions on their respective devices once imported._

To import your account using one of these methods, refer to the corresponding articles:

{% content-ref url="import-from-seed-phrase.md" %}
[import-from-seed-phrase.md](import-from-seed-phrase.md)
{% endcontent-ref %}

{% content-ref url="import-from-json-file.md" %}
[import-from-json-file.md](import-from-json-file.md)
{% endcontent-ref %}

{% content-ref url="import-from-private-key.md" %}
[import-from-private-key.md](import-from-private-key.md)
{% endcontent-ref %}

{% content-ref url="import-by-qr-code.md" %}
[import-by-qr-code.md](import-by-qr-code.md)
{% endcontent-ref %}
