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

Because Base64 is reversible, encoded data should never
be treated as confidential.
