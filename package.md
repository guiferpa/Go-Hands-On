# Pacotes

Go é organizada em pacotes, os nomes dos pacotes fornecem um contexto e um espaço de nomes.

```
import (
	"fmt"
)
```

O pacote rotateString criado para exemplificar vários conceitos.
https://github.com/crgimenes/rotateString


```
go get github.com/crgimenes/rotateString
```

Referencia completa ao pacote direto no código.

```
import (
	"fmt"
	r "github.com/crgimenes/rotateString"
)
```


Atualizar o pacote

```
go get -u github.com/crgimenes/rotateString
```

Exemplo de uso do pacote rotateString

```
package main

import (
	"fmt"
	r "github.com/crgimenes/rotateString"
)

func main() {
	s := r.Rotate("Isto é um teste de Rotate")
	fmt.Printf("rotate: %s\r\n", s)
}
```



---
[Inicio](README.md)
