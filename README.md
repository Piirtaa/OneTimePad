# OneTimePad
Single page web applications that facilitate one time pad encryption.  There are no external dependencies.  The term "one time pad" referring to the ancient technique of encoding data, not the currently overloaded application of the term that uses fancier and less-reliable cryptographic techniques.

otp.html provides encryption/decryption of a pad loaded from a local file.

padgen.html provides pad generation and mutation and saving to a local file.  

In all of the files above the use of a backing local file that can be read and persisted to is implemented in standard javascript, is cross-compatible with modern browsers, and does not suffer from the security restrictions of local file access that is commonly misunderstood to be show-stopping in more recent browsers.
