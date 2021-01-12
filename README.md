## AWS EC2 Backup Plans ##

The AWS Backup service can able to configure backup policies and monitor fully backup activities of the resources in your AWS accounts.

Ref: Documentation links for AWS Backup Service.

Basic concepts of backup:

https://docs.aws.amazon.com/aws-backup/latest/devguide/whatisbackup.html


Setup steps to backup policy:

https://docs.aws.amazon.com/aws-backup/latest/devguide/setting-up.html


Manage backup plans: (Creating, Assigning resources, deleting and updating backup plans)

https://docs.aws.amazon.com/aws-backup/latest/devguide/about-backup-plans.html


By default the backup service will backup linux machines but need to Enable windows VSS manually or also we can include within the template.

https://docs.aws.amazon.com/aws-backup/latest/devguide/windows-backups.html


                                        # Unsupported Amazon EC2 Instances #
                        
The following Amazon EC2 instance types are not supported for VSS-enabled Windows backups because they are small instances and might not take the backup successfully.

                t3.nano
                t3.micro
                t3a.nano
                t3.micro
                t2.nano
                t2.micro
