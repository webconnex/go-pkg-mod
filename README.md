go-pkg-mod
==========

Fork of core Go packages with modifications.

###### encoding/xml
- `xml:"Foo>Bar,omitempty"` will omit Foo if Bar is empty. From [issue 4168](https://code.google.com/p/go/issues/detail?id=4168), marked "Unfortunate".
