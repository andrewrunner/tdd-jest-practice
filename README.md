# ex-jest-first-steps

My experiments with Jest test library

1. AAA principles (ARRANGE-ACT-ASSERT)
2. F.I.R.S.T. principles (Fast, Independent, Repitable, Self-validating, Thorough) 


Use 
- VSCode "REST Client" extension for run  .http files 
- https://github.com/microsoft/vscode-recipes/tree/main/debugging-jest-tests



Jest hooks can help init common mocks for all tests;

Principles:
- One class = one test case.
- One method = one or more tests.
- One alternative branch (if/switch/try-catch/exception) = one test.

Doubles:
- Dummy object
- Fakes
- Stubs
- Spiec
- Mocks 



Пирамида тестов Майка Кона состоит из трёх уровней (снизу вверх):
- Юнит-тесты.
- Сервисные тесты.
- Тесты пользовательского интерфейса.
Из этой пирамиды главное запомнить два принципа:

Писать тесты разной детализации.
Чем выше уровень, тем меньше тестов.

