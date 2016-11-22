# Руководство по проектированию HTTP API 

Данное руководство описывает набор HTTP+JSON API методов проектирования, полученных при работе [Heroku Platform API](https://devcenter.heroku.com/articles/platform-api-reference).

This guide informs additions to that API and also guides new internal
APIs at Heroku. Мы надеемся что это руководство будет интересно не только сотрудникам Heroku.

Основная цель данного руководства - последовательное изложение, фокус на бизнес логике и избегание плохой архитектуры. Мы ищем _хорошие, последовательные,
хорошо документированные способы_ разработки API, но они не обязательно будут _идиальными и единственно верными_.

Мы предпологаем что вы знакомы с базой HTTP+JSON API и не будем охватывать базовые понятия в этом руководстве.

Руководство доступно для чтения online на [gitbook](https://www.gitbook.com/read/book/geemus/http-api-design).

Мы приветствуем [развитие](../CONTRIBUTING.md) этого руководста.

Вы можите ознакомиться с [оглавлением](SUMMARY.md) этого руководства.

### Переводы
 * [Portuguese version](https://github.com/Gutem/http-api-design/) (based on [fba98f08b5](https://github.com/interagent/http-api-design/commit/fba98f08b50acbb08b7b30c012a6d0ca795e29ee)), by [@Gutem](https://github.com/Gutem/)
 * [Spanish version](https://github.com/jmnavarro/http-api-design) (based on [2a74f45](https://github.com/interagent/http-api-design/commit/2a74f45b9afaf6c951352f36c3a4e1b0418ed10b)), by [@jmnavarro](https://github.com/jmnavarro/)
 * [Korean version](https://github.com/yoondo/http-api-design) (based on [f38dba6](https://github.com/interagent/http-api-design/commit/f38dba6fd8e2b229ab3f09cd84a8828987188863)), by [@yoondo](https://github.com/yoondo/)
 * [Simplified Chinese version](https://github.com/ZhangBohan/http-api-design-ZH_CN) (based on [337c4a0](https://github.com/interagent/http-api-design/commit/337c4a05ad08f25c5e232a72638f063925f3228a)), by [@ZhangBohan](https://github.com/ZhangBohan/)
 * [Traditional Chinese version](https://github.com/kcyeu/http-api-design) (based on [232f8dc](https://github.com/interagent/http-api-design/commit/232f8dc6a941d0b25136bf64998242dae5575f66)), by [@kcyeu](https://github.com/kcyeu/)
 * [Turkish version](https://github.com/hkulekci/http-api-design/tree/master/tr) (based on [c03842f](https://github.com/interagent/http-api-design/commit/c03842fda80261e82860f6dc7e5ccb2b5d394d51)), by [@hkulekci](https://github.com/hkulekci/)

