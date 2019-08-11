# Billing Alarms

Billing metrics are in the US East (N. Virginia) for all of AWS. This is an estimate of all the services in use on your account. It's good to set up a maximum threshold of `$` per month so when the limit is reached, you set a Simple Notification Service message off to an email that is monitored by you. This allows you to ensure none of the services used on Amazon Web Services costs you too much money. 

## Plan

The plan is to show how to setup a *billing alarm* in this order;

1. Create a Simple Notification Service (SNS) to a subscribed email.
2. Create a *billing alarm*.

> **Note**: For those trying to stick to a budget, note that it is an *estimate* and it could go up further.

Billing alerts are important to have in place so that AWS doesn't costs too much. Having unexpected costs at the end of the month is not a good thing. So let's ensure that this is setup properly to notify you when you hit your budget.

> *Next* read the [SNS setup](./sns-setup.md).
