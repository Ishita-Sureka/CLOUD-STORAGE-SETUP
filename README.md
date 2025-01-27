# CLOUD-STORAGE-SETUP

**COMPANY**:CODTECH IT SOLUTIONS

**NAME**:ISHITA SUREKA

**INTERN ID**:CT08IXT

**DOMAIN**:CLOUD COMPUTING

**BATCH DURATION**: December 30th, 2024 to January 30th, 2025

**MENTOR NAME**: NEELA SANTOSH

**DESCRIPTION OF TASK**:This task involves leveraging Amazon Web Services (AWS) Simple Storage Service (S3) to create, manage, and secure a cloud storage bucket. The goal is to set up an S3 bucket, upload example files, and configure access permissions to ensure secure and controlled access to the stored data. AWS S3 is a widely used cloud storage solution known for its reliability, scalability, and high availability. By completing this task, a solid understanding of how to use AWS S3 as a robust storage platform will be developed, alongside gaining practical experience with cloud security configurations.

The first step in the task was to create an S3 bucket, which serves as the storage container for data files. The bucket was given a unique name, complying with AWS naming conventions. During the creation process, specific configurations were chosen, including setting the bucket’s region to ensure data locality and performance optimization. With the bucket successfully created, it was ready to serve as a secure and scalable repository for file storage.

Following the bucket creation, example files were uploaded to demonstrate the storage and retrieval functionalities of AWS S3. The files represented data that might typically be stored in a cloud-based environment, such as documents, images, or configuration files. The upload process was straightforward, utilizing the AWS Management Console's intuitive interface. Each file uploaded was automatically assigned a unique object key, making it easy to identify and access the stored objects. The files’ metadata was also generated, including details such as file size, upload date, and storage class, which provide valuable insights for storage management.

The next critical step was configuring access permissions for the S3 bucket and its contents. By default, S3 buckets are private, and only the bucket owner has access. To allow secure and controlled access to the uploaded files, permissions were set using AWS Identity and Access Management (IAM). An IAM policy was created and attached to an IAM user to define the actions the user could perform on the S3 bucket, such as listing, uploading, downloading, or deleting files. This policy ensured that access was granted only to authorized individuals, adhering to the principle of least privilege.

In addition to configuring IAM policies, bucket policies were also implemented to further refine access control. A bucket policy is a resource-based policy written in JSON, specifying what actions are allowed or denied for users based on their IP address, identity, or other parameters. For this task, a simple bucket policy was added to restrict access to specific users and prevent unauthorized access from the public.

Finally, encryption was enabled to ensure the security of the data stored in the bucket. Server-Side Encryption (SSE) using AES-256 was configured, encrypting data at rest automatically. This measure ensured that even if unauthorized access occurred, the stored data would remain unreadable without the appropriate decryption keys.

By the end of this task, a fully configured S3 bucket was in place, complete with uploaded example files and secure access permissions. This hands-on activity not only showcased the capabilities of AWS S3 but also highlighted its importance as a reliable and secure cloud storage solution.

**OUTPUT OF TASK**:
![Image](https://github.com/user-attachments/assets/6f68b405-bb14-4602-a7a8-4aa8e73a22d9)
