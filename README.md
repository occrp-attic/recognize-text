# aleph-recognize-text

This is a service container that performs OCR on images
submitted as a byte stream by using `tesseract` 4.0. The
input should specify the language, if possible, so the
right type of script detection can be used.

Images submitted via the API should be limited to less
than 4 MiB in size, if possible, to avoid problems with
the gRPC protocol.
