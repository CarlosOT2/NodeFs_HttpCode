# NodeFs HttpCode # 
![Node Version](https://img.shields.io/badge/node-v20.11.1-yellow)
</br>
</br>

Pacote usado para retornar um código HTTP dependendo do código de error do node fs

<h3> Instalação </h3>
Para instalar o pacote, execute o comando <code>npm i nodefs_httpcode</code>
</br>
Utiliza o mecanismo de <b>ES Modules</b> para importar e exportar funções

<h3> Códigos De Error Suportados </h3>
<ul>
  <li><b>ENOENT</b> = <code>404</code></li>
  <li><b>EACCESS</b> = <code>403</code></li>
  <li><b>EROFS</b> = <code>403</code></li>
  <li><b>EEXIST</b> = <code>409</code></li>
  <li><b>ENOTEMPTY</b> = <code>409</code></li>
  <li><b>EMFILE</b> = <code>503</code></li>
  <li><b>ENFILE</b> = <code>503</code></li>
  <li><b>EINVAL</b> = <code>400</code></li>
  <li><b>EISDIR</b> = <code>400</code></li>
  <li><b>EIO</b> = <code>500</code></li>
  <li><b>ENOTDIR</b> = <code>500</code></li>
</ul>

exemplo de uso;
```javascript
import NodeHTTPCode from 'nodefs_httpcode'
const HttpCode = NodeHTTPCode(error) 
```
