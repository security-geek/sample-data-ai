# Amazon EBS encryption<a name="EBSEncryption"></a>

Use Amazon EBS encryption as a straight\-forward encryption solution for your EBS resources associated with your EC2 instances\. With Amazon EBS encryption, you aren't required to build, maintain, and secure your own key management infrastructure\. Amazon EBS encryption uses AWS Key Management Service \(AWS KMS\) customer master keys \(CMK\) when creating encrypted volumes and snapshots\.

Encryption operations occur on the servers that host EC2 instances, ensuring the security of both data\-at\-rest and data\-in\-transit between an instance and its attached EBS storage\.

You can attach both encrypted and unencrypted volumes to an instance simultaneously
