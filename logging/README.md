# KD4A Logging Golden Path

Best practices and approaches for logging in our apps.

## Approach

- We use the ELK Stack for our log monitoring and analysis needs.
- Our apps send logs to a configured Logstash instance.
- The logs follow the [RFC5424 SysLog](https://tools.ietf.org/html/rfc5424) standard

## Tooling

- For JavaScript/TypeScript stacks we recommend [Winston](https://github.com/winstonjs/winston)
- For any other purposes we recommend any logger that integrates with Logstash
