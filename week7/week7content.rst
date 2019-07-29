Nutanix Certified Professional
==============================

NCP Training
++++++++++++
.. sidebar:: Expected duration

    3 days for the sessions

.. note:: **Objective:** To prepare the ASEs in taking their NCP


NCP Blueprint Review
--------------------

Explain : Review the NCP exam criteria and explain the testing environment requirements

Content : Available through Portal (https://nutanix.portal.relayware.com/content/EDUCollateral/NCP5.5-EBG-1.26.2019.pdf)


NCP Cram Session
----------------

Explain : Run through the focus topics

Content : Slides and use of Nutanix Cluster for queries

----

NCP Cram Session (continued)
----------------------------

Explain : Run through the focus topics

Content : Slides and use of Nutanix Cluster for queries

----

NCP Final Prep and Exam
-----------------------

Explain : Use the sample mock questions below and get the exam booked

Content : Questions below and website to book exam

Questions for the class
~~~~~~~~~~~~~~~~~~~~~~~
**Question 1:** What file system would be presented when using Microsoft's Hyper-V on Nutanix?

- NFS
- iSCSI
- SMB

**Question 2:** What would be the expected storage gain when EC-X is enabled on an NX-3360-G6?

- 25%
- 50%
- It depends
- None

**Question 3:** A customer has configured Cloud Connect, what Cloud Providers can they use?

- Google (GCP)
- Nutanix (Xi Leap)
- Amazon (S3)
- Microsoft Azure (Storage blobs)
- Rackspace (Infinity)

**Question 4:** A customer wants to implement Nutanix but a competitor has told them they'd have to virtualise all their physical servers for Nutanix to work. The customer has to keep their MS SQL and Oracle database servers because of licensing reasons. What should the SE suggest?

- Virtualise the database servers but use low core count CPUs to reduce license cost, use affinity rules to keep them fixed to these servers
- Suggest to the customer they use Nutanix Volumes and present storage via iSCSI to the existing physical servers
- Advise the customer to leave their physical servers out of the scope of this project and buy NAS equipment which would keep costs down
- Migrate the databases to a Cloud provider's hosted service

**Question 5:** A critical workload needs to be guaranteed high performance and low latency if it's to be moved to a Nutanix Cluster, what would you suggest to a customer?

- Advise them all 'hot' data resides in the SSD tier so in a hybrid configuration it wouldn't affect the application's performance
- Suggest they keep the workload away from Nutanix and buy dedicated hardware from another vendor that specialises in low latency applications
- Use VM Pinning to fix the workload to the SSD tier

**Question 6:** Planning is an important consideration for a customer and they'd ideally like to have some forecasting capability of the environment so they can predict future expansion as they expect multiple mergers in the coming years. What could you recommend?

- Use Prism Element to monitor disk utilisation and use a spreadsheet to track the changing states
- Enable SNMP to send information to a 3rd party tool to model consumption
- Install Prism Central and purchase Prism Pro to access the Planning and Runway feature
- In Prism Element select Hardware, Diagram and Disk. Sort the disks by their 'type' and review the consumption.
