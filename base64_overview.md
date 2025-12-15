## Base64 Overview

Base64 is a binary-to-text encoding scheme that converts binary data (like images, files) into a safe, printable ASCII string format (using 64 characters) for reliable transmission over text-based systems.

It is commonly used in:
- Email systems
- Data URLs
- HTTP basic authentication
- Embedding small data blobs in web pages

Base64 output usually contains:
- Uppercase and lowercase letters
- Numbers
- '+' and '/'
- Optional '=' padding at the end

Important distinctions
- Not Compression: It makes data bigger (by ~33%), it doesn't reduce size.
- Not Encryption: It's easily reversible; anyone can decode it without a key, so don't use it for secrets. 
