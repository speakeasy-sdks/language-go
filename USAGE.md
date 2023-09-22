<!-- Start SDK Example Usage -->


```go
package main

import(
	"context"
	"log"
	languagego "github.com/speakeasy-sdks/language-go"
)

func main() {
    s := languagego.New()

    ctx := context.Background()
    res, err := s.Pets.CreatePets(ctx)
    if err != nil {
        log.Fatal(err)
    }

    if res.StatusCode == http.StatusOK {
        // handle response
    }
}
```
<!-- End SDK Example Usage -->