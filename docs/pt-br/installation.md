# Instalação

### Download direto / CDN

[https://unpkg.com/vue-router/dist/vue-router.js](https://unpkg.com/vue-router/dist/vue-router.js)

<!--email_off-->
[Unpkg.com](https://unpkg.com) fornece links CDN baseados no npm. O link acima sempre apontará para a última versão no npm. Você também pode usar uma versão / tag específica via URLs como `https://unpkg.com/vue-router@2.0.0/dist/vue-router.js`.
<!--/email_off-->

Inclua `vue-router` após o Vue e ele se instalará automaticamente:

``` html
<script src="/path/to/vue.js"></script>
<script src="/path/to/vue-router.js"></script>
```

### npm

``` bash
npm install vue-router
```

Quando usado com um sistema de módulos, você deve instalar explicitamente o _router_ via `Vue.use()`:

``` js
import Vue from 'vue'
import VueRouter from 'vue-router'

Vue.use(VueRouter)
```

Você não precisa fazer isso ao usar tags de _script_ globais.

### Versão de desenvolvimento

Você terá que clonar o repositório diretamente do GitHub e construir o `vue-router` você mesmo se deseja usar a última versão de desenvolvimento.

``` bash
git clone https://github.com/vuejs/vue-router.git node_modules/vue-router
cd node_modules/vue-router
npm install
npm run build
```
