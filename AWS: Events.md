# AWS: Events

### AWS SQS vs SNS

- Difference: SQS - Message queuing, SNS - Publish/Subscribe.
- Use cases: SNS - Push notifications, SQS - Decoupling components.

### AWS SNS and SQS

- Fanout pattern: SNS broadcasts to multiple SQS queues.
- Push notifications: SNS sends messages directly to subscribers' devices.

### SQS and SNS Basics

- Large-scale use: SQS manages queues between distributed components.
