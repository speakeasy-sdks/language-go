<!-- Start SDK Example Usage [usage] -->
```go
package main

import (
	"context"
	languagego "github.com/speakeasy-sdks/language-go"
	"log"
)

func main() {
	s := languagego.New()

	ctx := context.Background()
	res, err := s.Pets.CreatePets(ctx)
	if err != nil {
		log.Fatal(err)
	}
	if res != nil {
		// handle response
	}
}

```
<!-- End SDK Example Usage [usage] -->