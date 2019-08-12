# Identity, Access, and Access Management (IAM) Notes

* IAM does not reside within a single region, the users, groups, and role can be applied to all regions.
* **Root Account** - is the account created when first setup the AWS account and has complete administrator access.
    * Always turn on multi-factor authentication (MFA) for the *root account* (always good practice for the other users on the AWS Account as well).
* No new users have *any* permissions when created.
    * Are assigned Access Key ID & Secret Access keys when first created.
    * Types of access for users;
        1. **Console Access** - Through AWS website via a username and password.
        2. **Programmatic Access** - Used for interacting with AWS through code typically via a programming or scripting language.
            * Not the same as the password.
            * Used via the *Access Key ID* and *Secret Access Key*.
            * Cannot be used to log into the console.
            * May view only once, otherwise you will have to regenerate them.
* Ensure you customization smart policies applied to a rotation, types of characters and the length of passwords.
