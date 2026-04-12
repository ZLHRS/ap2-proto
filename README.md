# Assignment 2 - Proto Repository

This repository serves as the central source of truth for all gRPC contracts (`.proto` files) used in Assignment 2.

It adheres to a development approach, meaning all service APIs and models are strictly defined here independently of the microservice implementations.

## Repository Structure
```text
.
├── README.md
└── proto
    ├── order
    │   └── v1
    │       └── order.proto
    └── payment
        └── v1
            └── payment.proto
```

## Setup and Usage

Your individual microservices (e.g. Order Service, Payment Service) will import the pre-built gRPC code directly from the Generated Repository. This keeps application logic entirely separate from the gRPC definition files.
