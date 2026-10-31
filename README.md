Archive: 123.zip
Original size: 4932547008 bytes
Original SHA-256: b4ac436462930e45e5d697844fa77a84596a732b30da405d58f16d6f7ef1f396

Download all five part files into one directory. These are byte-for-byte
segments of the original ZIP file, not individually extractable archives.
Reassemble and verify on Linux or macOS:

  sha256sum -c SHA256SUMS.parts
  cat 123.zip.part00 123.zip.part01 123.zip.part02 123.zip.part03 123.zip.part04 > 123.zip
  sha256sum 123.zip

The final hash must match the original SHA-256 above.
