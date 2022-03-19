# Logging in Spring Boot

- Spring Boot uses Commons Logging for all internal logging. But it keeps underlying implementations open, i.e., different libraries can be used to log with the help of Commons Logging. For example, Logback, Log4J2, Java Util Logging.

- By default, when any "Starter" is used, "Logback" is included for logging.

- Default Log output in Spring has the following format:
    - < Date > < Time > < Log Level > < Process Id > <---> < Thread Name > < Logger Name > < Log Message >