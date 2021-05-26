
##Manipulando objeto
###importando classe
```
from documento.models import Documento
```
###Criando objeto
```
Documento.objects.create(nome="12351asdasd")
```

###Listar
```
documentos = Documento.objects.all()
```

###Filtrar
```
documento = Documento.objects.filter(id=1)
```

###Atualizar
```
documento.update(nome="novo nome")
```
###Deletar
```
documento.delete()
```