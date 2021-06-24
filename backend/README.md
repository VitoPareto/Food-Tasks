W przypadku problemów z uruchomieniem skryptów npm w systemie windows,
do zależności została dodana biblioteka 'cross-env'
(https://www.npmjs.com/package/cross-env)

exmpl:
"start:dev": "cross-env STAGE=dev nest start --watch",
