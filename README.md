# AWS S3-Bucket Creation 

Steps Completed  :
    1. Bucket Creation and Configuration:
          > An S3 bucket named "object-storage-basics-1" was created in an AWS Region (US-east-1).
          > S3 Versioning Was enabled on the bucket.
    2. Object upload : A PDF file, "docker-notes.pdf",was succesfully uploaded to the root of the bucket
    3. Permission Configuration : To make the object accessible via  a public URL, the following permission 
       changes were made :
          > Block Public Access Settings : The default "Block all public access" setting for the buket was               disabled.         
          > ACLs Enabled : Access Control List(ACLs) were enbaled for the bucket to allow for setting 
            permissions on individual objects
          > Object-Level Permissions: The docker-notes.pdf object was made public by modifying its ACL to                grant  "Read" acceess to "Eveyone(public access)"                
          
