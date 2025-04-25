# NodeFs HttpCode # 
![Node Version](https://img.shields.io/badge/node-v20.11.1-yellow)
<br/>
<br/>
<b>A documentação está disponível em português. Você pode alternar para o português clicando em [Versão português](README.pt.md)</b>

Package used to return an HTTP status code depending on the error code from node fs

<h3> Install </h3>
to install the package, run the command <code>npm i nodefs_httpcode</code>
</br>
uses <b>ES Modules</b> mechanism to import and export functions

<h3> Supported Error Codes </h3>
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

Usage example;
```javascript
import NodeHTTPCode from 'nodefs_httpcode'
const HttpCode = NodeHTTPCode(error) 
```

