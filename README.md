## Команды для запуска тестов из терминала

### Запуск тестов локально

#### Все тесты

```bash
gradle clean all_tests -Denvironment=local 
```
#### Только позитивные

```bash
gradle clean positive_tests -Denvironment=local
```
#### Только негативные

```bash
gradle clean negative_tests -Denvironment=local
```


### Запуск тестов удаленно Selenoid 

#### Все тесты

```bash
gradle clean all_tests -Denvironment=remote 
```
#### Только позитивные

```bash
gradle clean positive_tests -Denvironment=remote
```
#### Только негативные

```bash
gradle clean negative_tests -Denvironment=remote
```
