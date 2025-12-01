# Steps Taken — IAM Project

1. Created IAM groups:
   - ReadOnlyGroup
   - AdminGroup
2. Attached appropriate managed policies:
   - ReadOnlyAccess
   - AdministratorAccess
3. Created users:
   - test-readonly
   - test-admin
4. Added users to their groups.
5. Tested login for each user:
   - ReadOnly user correctly denied access for restricted actions.
   - Admin user had full permissions.
