## <p align="center"><ins>DCUI Console Keys</ins></p>

| Description | Shortcuts|
| :--- | :---: |
| Switches to the console| ***ALT+F1***|
| Switches to the DCUI| ***ALT+F2***|
| Returns to the banner screen| ***ALT+F11***|
| Displays the VMkernel log on the console| ***ALT+F12***|

## <p align="center"><ins>Storage</ins></p>

| Description | Command |
| :--- | :---: |
| get the naa.id or label name of the Datastore/LUN | ***esxcli storage vmfs extent list*** <br />|
| generate a list of all LUN paths currently connected | ***esxcli storage core path list***<br /> ***esxcli-scsidevs -l*** <br /> ***esxcli storage vmfs extent list*** <br/>***esxcli storage filesystem list***|
| command to list out all the VMFS backed datastores | ***esxcfg-scsidevs -m*** |
| get the list of permanently detached devices | ***esxcli storage core device detached list*** |br/
| detach a device/LUN | ***esxcli storage core device detached list*** |
| get the list of permanently detached devices | ***esxcli storage core device detached list***|
| detach a device/LUN | ***esxcli storage core device detached list***|
| verify that the device is offline (The output, which shows that the status of the disk is off,) | ***esxcli storage core device list -d <NAA ID>***|
| Permanently remove the device configuration information from the system | ***esxcli storage core device detached remove -d <NAA ID>***|
| rescan hba for LUNS\Storage | ***esxcli storage core adapter rescan -A vmhbaX \| –all*** |
| Unmount the datastore | ***esxcli storage filesystem unmount -u uuid \| -l lable \| -p path***|
|| ***esxcli storage filesystem unmount -l LUN01*** |
|| ***esxcli storage filesystem unmount -u 4e414917-a8d75514-6bae-0019b9f1ecf4***|
|| ***esxcli storage filesystem unmount -p /vmfs/volumes/4e414917-a8d75514-6bae-0019b9f1ecf4***|

## <p align="center"><ins>Important urls</ins></p>

| Description | urls|
| :--- | :---: |
| esxtop Guide | ***https://www.virten.net/vmware/esxtop/*** |
| vscsiStats   | ***http://www.yellow-bricks.com/2009/12/17/vscsistats/***|
| vscsiStats   | ***http://www.gabesvirtualworld.com/converting-vscsistats-data-into-excel-charts/***|
 
