Sizing (Theory) & Objection Handling
====================================

Sizing
++++++
.. sidebar:: Expected duration

    1 day for the session

.. note:: **Objective:** Overview the need for sizing Nutanix and a common approach to fact finding

Data gathering
--------------

Explain : Use the headings below to frame the common discovery questions, delve into each topic to further expand knowledge of IT

Content : Interactive whiteboard, URL that can be used as an extra workshop http://ntnx.tips/sizingref

-  Data gathering

   -  Application(s) hosted the on virtualised estate

   -  Current hardware deployment(s)

   -  Quantity of DCs

   -  LAN / WAN (including bandwidth and latency)

   -  Current hypervisor(s) and management tool(s)

   -  vCPU / RAM / Disk

   -  Business Continuity Planning and Disaster Recovery

      -  Today  (RPO and RTO phrases)

      -  Aspiration

   -  Backup

      -  Rate of change (daily)

-  Tools

   - Nutanix Collector extracts information from VMware environments via VMware's vCenter and exports the data into an XLSX format

   - VMware environments can be scanned using a free tool called RVTools, this outputs all details of the VMs to a .CSV file which can be imported directly into Nutanix Sizer

   - Dell's LiveOptics can scan and capture physical and virtual workloads over a period time providing utilisation metrics, better for environments where peak workload processing periods need to be taken into consideration. Note, Dell will be notified when a customer signs up so consider the impact for the opportunity

----

Objection Handling
++++++++++++++++++
.. sidebar:: Expected duration

    Half day for the session

.. note:: **Objective:** Understand the common push backs from customers and how to deal with them

Common responses
----------------

Explain : (content to be added after speaking with Paul)

Content : Interactive whiteboard and role play
