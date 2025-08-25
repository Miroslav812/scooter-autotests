# Scooter UI Tests (Java 11 + JUnit5 + Selenium)

## Requirements
- Java 11 (SDK)
- Maven
- Google Chrome and/or Mozilla Firefox

## Run
- Default (Chrome):
```bash
mvn clean test
```
- Firefox:
```bash
mvn clean test -Pfirefox
```
- Explicit Chrome:
```bash
mvn clean test -Pchrome
```

WebDriver binaries are managed automatically via WebDriverManager.
