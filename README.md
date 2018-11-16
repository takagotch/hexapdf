### hexapdf
---
https://github.com/gettalong/hexapdf

```ruby
require 'heaxapdf'
doc = HexaPDF::Document.new
canvas = doc.pages.add.canvas
canvas.font('Helvetica', size: 100)
canvas.text("Hello", at: [20, 400])
doc.write("hello.pdf")
```

```
```

```
```



