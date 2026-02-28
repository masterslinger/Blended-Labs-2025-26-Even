# Lab 4 – Working with Amazon Elastic Block Store (EBS)

## Author

* **Name**: Syed Abu Hanifa
* **Register Number**: 212224040346
* **Date of Submission**: 28/02/2026

---

## Objective

The objective of this experiment is to understand how Amazon Elastic Block Store (EBS) provides persistent block-level storage for EC2 instances. This lab focuses on creating and attaching an EBS volume, formatting and mounting it on an EC2 instance, storing data, and verifying data persistence after instance reboot.

---

## Prerequisites

* Basic understanding of cloud computing concepts
* AWS account or AWS Academy Lab access
* An existing EC2 instance (Amazon Linux 2 preferred)
* Basic knowledge of Linux commands

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Amazon EBS
* SSH Client (Terminal / PuTTY)

---

## Tasks Performed

### Task 1: Explore Amazon EBS

Explore the Amazon EBS service through the EC2 dashboard. Observe different volume types such as General Purpose SSD (gp2/gp3), Provisioned IOPS SSD, Throughput Optimized HDD, and Cold HDD.

---

### Task 2: Create an EBS Volume

Create a new EBS volume in the same Availability Zone as the EC2 instance. Choose an appropriate size and volume type.

---

### Task 3: Attach EBS Volume to EC2 Instance

Attach the created EBS volume to the running EC2 instance as an additional block device.

---

### Task 4: Format the EBS Volume

Connect to the EC2 instance using SSH and format the attached volume with a file system (for example, ext4).

---

### Task 5: Mount the EBS Volume

Mount the formatted volume to a directory in the EC2 instance (for example, /data or /mnt/ebs).

---

### Task 6: Store Data in EBS Volume

Create files and directories inside the mounted EBS volume and store sample data.

---

### Task 7: Verify Data Persistence

Reboot the EC2 instance and verify that the data stored in the EBS volume is still available after reboot.

---

## Workflow (Student Explanation)

(Write the steps you followed in your own words)

1. Created an Amazon EBS volume

2. Attached the volume to an EC2 instance

3. Created a file system on the volume

4. Added a file to volume

5. Created a snapshot of volume

6. Created a new volume from the snapshot

7. Attached and mounted the new volume to the EC2 instance

8. Verified that the file created earlier was on the newly created volume


---

## Output Screenshots (Attach 3)

### Screenshot 1: EBS Volume Created

<img width="2048" height="908" alt="image" src="https://github.com/user-attachments/assets/68f9aaea-0eae-4795-a594-334d8173d426" />



---

### Screenshot 2: EBS Volume Attached to EC2
<img width="1919" height="1199" alt="Screenshot 2026-02-28 193406" src="https://github.com/user-attachments/assets/81e22f60-55b2-46e8-82c2-556f52ebc567" />



---

### Screenshot 3: Mounted Volume with Data
<img width="1919" height="1199" alt="Screenshot 2026-02-28 193401" src="https://github.com/user-attachments/assets/7d06d8d8-ae8a-4f33-8b20-8f44a3ca70ce" />




---

## Result / Conclusion

This experiment demonstrated how Amazon EBS provides persistent storage for EC2 instances. By creating, attaching, formatting, and mounting an EBS volume, and by verifying data after reboot, the concept of durable block storage in the cloud was clearly understood.
