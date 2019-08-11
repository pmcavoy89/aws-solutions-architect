# Identity Access Management (IAM)

## Introduction
**Identity Access Management** is a way to manager users sand access level to the AWS console.

> **Note**: Correctly applying the right level of access is important for security reasons.

## Features
    
* Includes shared access to AWS account.
* Setting permissions for users on the account.
* **Identity Federation** - Allows other sources for storing information on the Identity Access Management.
* Enable multi-factor authentication.
* Provide temporary access for user or device.
* Set up password rotation policy.
* Supports Payment Card Industry Data Security Standard (PCI DSS Compliance).

## Key Terms

* **Users** - End users (such as people, or an application).
* **Groups** - Collection of users. Users will also get permissions from group.
* **Policies** - Are documents, in Javascript Standard Object Notation (JSON), that give the permissions for users, groups, and roles
* **Roles** - Assigned to AWS resources so that it may communicate with another feature provided by AWS. A good example is to allow a Lambda to write to an S3 bucket.


> **Up Next**: [IAM Notes](./notes.md)
