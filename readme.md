# GOWIN IP Folder Template readme

* 1_Doc

  * 1_DesignSpec
    * referece of the IP design
    * Design Specification document
  * 2_Test_Spec
    * Cases of the IP have been tested
  * 3_GUIMake
    * GUI markdown file for EDA team to know how to build the IP interface on EDA
* 2_FPGA

  * Board Test project
* 3_Code

  * 1_ipcore
    * Source code of the IP
  * 2_src_gui
    * Encrpted Source code of the IP
* 4_Verification

  * Verification script
  * IP simulation (Modelsim)
* Ref. Design of the this IP Project
* User manual for the IP releast DOCS (For public)
* IP feature DOCS
* IP release or update DOCS (For internal)

# Processes for a New IP Release

1. Create and Finish this folder's requirements
2. Upload the required Documents and code to `Import` (a folder of the virtual computer)
3. Inside the Virtual computer:
   1. Create a page for the IP on twiki
   2. Update the Device Support of the IP
   3. Issue a task on Mantis (Internal)
   4. Check in the `Source code of the IP` to SVN in Linux
4. Capture the Mantis task and sent to software team on wecom(chunxiang)
5. Send the User manual documents to Docmentation team
6. After the EDA update using the updated EDA to Generate The IP's Reference Design
   1. capable with Simualtion and BoardTest
7. Send the Ref. Design though wecom
8. Upload the `IP release or update DOCS` to Gowin drive

**Delete this file after create**

Last Update: 2/12/2024 Antony
