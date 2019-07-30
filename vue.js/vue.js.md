## Estrutura de diretórios para projetos Vue.js
* config/               -> arquivos para configuração de Environments 
* src/                  -> Contêm todos código fonte da aplicação
    + assets/           -> diretório para arquivos estáticos
    + common/           -> componentes comum a todos
    + components/       -> estrutura de componentes especificos do projeto
    + directives/       -> diretório para diretivas
    + filters/          -> filters que serão utilizados nos components
    + layouts/          -> diretório para a base do layout que sera utilizado nas views
    + mixins/           -> Mixins Vue usado no projeto
    + plugins/          -> diretório para plugins
    + services/         -> diretório para os serviços
    + views/            -> views com a interface do projeto
    + app.vue           -> componente principal da aplicação
    + helpers.vue       -> arquivos de funções puras em js
    + main.js           -> arquivo para importar e criar a instância Vue
    + router.js         -> arquivo para configuração de rotas
* static/               -> diretório para os arquivos estaticos
* test/                 -> arquivos relcionados aos testes
