## <p align="center"><ins>DCUI Console Keys</ins></p>
<div align="center">

| Description | Shortcuts|
| :--- | :--- |
| Switches to the console| ***ALT+F1***|
| Switches to the DCUI| ***ALT+F2***|
| Returns to the banner screen| ***ALT+F11***|
| Displays the VMkernel log on the console| ***ALT+F12***|

## <p align="center"><ins>Storage</ins></p>

| Description | Command |
| :--- | :--- |
| get the naa_id or label_name of the Datastore/LUN | ***esxcli storage core path list***<br /> ***esxcli-scsidevs -l*** <br /> ***esxcli storage vmfs extent list*** <br/>***esxcli storage filesystem list***|
| get the list of permanently detached devices | ***esxcli storage core device detached list*** |
| get the list of permanently detached devices | ***esxcli storage core device detached list***|
| verify the device status | ***esxcli storage core device list -d <NAA ID>***|
| detach a device/LUN | ***esxcli storage core device detached remove -d naa_id*** |
| Permanently remove the device configuration <br/>information from the system | ***esxcli storage core device detached remove -d <NAA ID>***|
| rescan hba for LUNS\Storage | ***esxcli storage core adapter rescan -A vmhbaX \| –all*** |
| Unmount the datastore | ***esxcli storage filesystem unmount -u uuid \| -l lable \| -p path***<br/><br/> <ins>example:</ins> <br/> ***esxcli storage filesystem unmount -l LUN01*** <br/> - ***esxcli storage filesystem unmount -u 4e414917-a8d75514-6bae-0019b9f1ecf4*** <br/> ***esxcli storage filesystem unmount -p /vmfs/volumes/4e414917-a8d75514-6bae-0019b9f1ecf4***|

## <p align="center"><ins>Important urls</ins></p>

| Description | urls|
| :--- | :---: |
| esxtop Guide | ***https://www.virten.net/vmware/esxtop/*** |
| vscsiStats   | ***http://www.yellow-bricks.com/2009/12/17/vscsistats/***|
| vscsiStats   | ***http://www.gabesvirtualworld.com/converting-vscsistats-data-into-excel-charts/***|
|How to Remove Storage Devices from ESXi Hosts|***https://lazyadminblog.com/2015/11/21/how-to-remove-storage-devices-from-esxi-hosts/***|
 
</div>