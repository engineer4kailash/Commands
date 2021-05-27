## <p align="center"><ins>Storage</ins></p>
| Description | Command |
| :--- | :---: |
| get the naa.id or label name of the Datastore/LUN | ***esxcli storage vmfs extent list*** |
| get the list of permanently detached devices | ***esxcli storage core device detached list*** |
| To detach a device/LUN | ***esxcli storage core device detached list*** |
| get the list of permanently detached devices | ***esxcli storage core device detached list***|
| To detach a device/LUN | ***esxcli storage core device detached list***|
| To verify that the device is offline (The output, which shows that the status of the disk is off,) | ***esxcli storage core device list -d <NAA ID>***|
| Permanently remove the device configuration information from the system | ***esxcli storage core device detached remove -d <NAA ID>***|
| rescan hba for LUNS\Storage | ***esxcli storage core adapter rescan [ -A vmhba# \| –all ]***|


| Description | Urls|
| :--- | :---: |
| esxtop Guide | ***https://www.virten.net/vmware/esxtop/*** |
| vscsiStats   | ***http://www.yellow-bricks.com/2009/12/17/vscsistats/***|
| vscsiStats   | ***http://www.gabesvirtualworld.com/converting-vscsistats-data-into-excel-charts/***|
 
