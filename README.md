### CI
[Лекция про сборку и CI]

[dartvm by mraleph] - про внутреннее устройство dart vm

[codemagic] - простой сервис для сборок приложений на flutter

[github actions] - дока по github actions (для публичных репозиториев можно использовать бесплатно практически без ограничений)

[flutter deployment] - оффициальная дока по подготовке приложения к публикации

[flutter CI/CD] - оффициальные рекомендации по настройки CI/CD

### Тесты
[Лекция про тесты] 

[SOLID] - очень классный доклад хорошо раскрывающий принципы SOLID, очень советую посмотреть полностью (он сделан в контексте java и spring, но очень доступно для любого бекграунда)

[Fowler docs] - моки, стабы и другие звери

[Fowler test pyramid] - пирамида тестирования на практике

[docs] - документация про тесты

[integration_test docs] - подробнее про интеграционные тесты

[mockito] - пакет для использования моков, поддерживает работу как через reflection, так и через генерацию кода (генерация нужна для запуска в aot режиме, например для интеграционных тестов в profile сборке)

[golden_toolkit] - набор тулзов для удобной работы с golden тестами, включает в себя набор утилит для поддержки шрифтов и любых других ассетов

[flutter/test] - кладезь всевозможных примеров тестов, да и вообще в репозитории флаттера можно очень много информации почерпнуть

[Official plugins rules] - хорошо расписано в контексте репозитория плагинов поддерживаемых командой flutter


<!-- Links -->
[Лекция про тесты]: ./docs/Tests.pdf
[SOLID]: https://www.youtube.com/watch?v=rd6wxPzXQvo
[Fowler docs]: https://martinfowler.com/articles/mocksArentStubs.html
[Fowler test pyramid]: https://martinfowler.com/articles/practical-test-pyramid.html
[docs]: https://docs.flutter.dev/testing
[integration_test docs]: https://docs.flutter.dev/testing/integration-tests
[mockito]: https://pub.dev/packages/mockito
[golden_toolkit]: https://pub.dev/packages/golden_toolkit
[flutter/test]:https://github.com/flutter/flutter/packages/flutter/test
[Official plugins rules]: https://github.com/flutter/flutter/wiki/Plugin-Tests


[Лекция про сборку и CI]: ./docs/Build_CI.pdf
[dartvm by mraleph]: https://mrale.ph/dartvm/
[codemagic]: https://codemagic.io/start/
[github actions]: https://docs.github.com/en/actions
[flutter deployment]: https://docs.flutter.dev/deployment/
[flutter CI/CD]: https://docs.flutter.dev/deployment/cd