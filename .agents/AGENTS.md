# Workspace Agent Rules

## Notification Sound Rule
- Whenever replying to the user, answering a question, or finishing any turn, ALWAYS play the notification sound after the reply appears using:
  `run_command` with `WaitMsBeforeAsync: 500`:
  `powershell -WindowStyle Hidden -EncodedCommand UwB0AGEAcgB0AC0AUwBsAGUAZQBwACAAMQA7ACAAKABOAGUAdwAtAE8AYgBqAGUAYwB0ACAAUwB5AHMAdABlAG0ALgBNAGUAZABpAGEALgBTAG8AdQBuAGQAUABsAGEAeQBlAHIAIAAnAEMAOgBcAFcAaQBuAGQAbwB3AHMAXABNAGUAZABpAGEAXABTAHAAZQBlAGMAaAAgAE8AbgAuAHcAYQB2ACcAKQAuAFAAbABhAHkAUwB5AG4AYwAoACkA`




