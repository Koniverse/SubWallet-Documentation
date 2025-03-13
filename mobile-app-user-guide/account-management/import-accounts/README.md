---
description: Import your existing accounts onto SubWallet using backup information.
---

# Import accounts

### Supported import methods <a href="#supported-import-methods" id="supported-import-methods"></a>

You can import your existing accounts onto SubWallet via one of the following methods: seed phrase, JSON file, private key, or QR code.

<table><thead><tr><th width="199">Account type</th><th data-type="checkbox">Seed phrase</th><th data-type="checkbox">JSON file</th><th data-type="checkbox">Private key</th><th data-type="checkbox">QR code</th></tr></thead><tbody><tr><td>Unified account</td><td>true</td><td>true</td><td>false</td><td>false</td></tr><tr><td>Substrate account</td><td>false</td><td>true</td><td>false</td><td>true</td></tr><tr><td>EVM account</td><td>false</td><td>true</td><td>true</td><td>true</td></tr><tr><td>TON account</td><td>true</td><td>true</td><td>true</td><td>false</td></tr><tr><td>Ledger account*</td><td>false</td><td>true</td><td>false</td><td>false</td></tr><tr><td>QR-signer account*</td><td>false</td><td>true</td><td>false</td><td>false</td></tr></tbody></table>

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
