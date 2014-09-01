veeam-create-backup-jobs
========================

This simple powershell script automatically creates Veeam backup jobs for all virtual machines VMware vSphere, including the new ones.

Features:
* It uses the official powershell VEEAM and VMWARE API.
* Separate job per every virtual machine.
* Allow multiple vCenter servers.
* Resource based excluded and user defined excluded.
* Run backup jobs in multiple paralel threads.

Installation:
* Install necessary powershell snapins.
* Add this script as job to the Windows scheduler. For example, at 5 pm everyday if first backup starts at 6 pm.
