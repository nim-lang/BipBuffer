# BipBuffer
A Nim implementation of Simon Cooke's [Bip Buffer]  A Bi-partite buffer is similar to a circular buffer, but wheredata is inserted in two revolving regions. This allows reads to return contiguous blocks of memory, even if they span a region that would normally include a wrap-around in a circular buffer. It's especially useful for APIs requiring blocks of contiguous memory, eliminating the need to copy data into an interim buffer before use.
