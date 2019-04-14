# TP1 Especificaciòn de Software

TP1 app "Todo Inversiones"

## Ver cambios en los docxs

  - Instalar Pandoc http://pandoc.org/installing.html
  - Crear o editar archivo ~/.gitconfig (linux, Mac) o "c:\Documents and Settings\user.gitconfig"(Windows) y agregar

```sh
[diff "pandoc"]
   textconv=pandoc --to=markdown
   prompt = false
 [alias]
   wdiff = diff --word-diff=color --unified=1
```
- Para ver diferencias con el ùltimo commit
```sh
git wdiff file.docx
```
- Para ver todos los cambios a lo largo del tiempo

```sh
git log -p --word-diff=color file.docx
```

Para màs info https://github.com/vigente/gerardus/wiki/Integrate-git-diffs-with-word-docx-files
