+++
title = "Hello"
date = 2022-06-14T23:03:20-04:00
weight = 6
chapter = true
pre = "<b>X. </b>"
+++

### Chapter X

# Some Chapter title

Lorem Ipsum.

_ooh look italicized text!_

here's an example of syntax highlighting:

```go
func (s *DocumentService) List(ctx context.Context, req *sharedmonorepo.DocumentListRequest) (*sharedmonorepo.DocumentListResponse, error) {
    // do stuff . . .
    return nil, werror.New("unimplemented").SetCode(werror.CodeUnimplemented)
}
```
