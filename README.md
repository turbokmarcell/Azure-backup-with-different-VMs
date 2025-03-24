# Azure VM Backup to Recovery Services Vault

This project demonstrates how to back up Azure Virtual Machines (VMs) using Azure Backup and store them in a Recovery Services Vault.  

## **Tested Scenarios**  
- Backing up VMs running Windows Server 2012 or higher  
- Backing up VMs running Debian 8.2+
- Backing up VM running Windows 10 
- Backing up running (not shut down) VMs
- Backing up shut down (deallocated) VM

## **Demo Video**  
Watch the full test video here: [Youtube video](https://www.youtube.com/watch?v=q13woBsS5Ig)  

## **Steps to Reproduce**  
1. Create a Recovery Services Vault in the Azure portal.  
2. Configure a Backup Policy.  
3. Select the supported VMs and enable backup.  
4. Trigger a manual backup to verify functionality.


# Azure VM biztonsági mentés a Recovery Services Vault-ba

Ez a projekt bemutatja, hogyan lehet Azure Virtual Machines (VMs) példányokat biztonsági menteni az Azure Backup segítségével, és tárolni egy Recovery Services Vault-ban.  

## **Tesztelt forgatókönyvek**  
- Windows Server 2012 vagy újabb verziójú VM mentése  
- Debian 8.2+ verziójú VM mentése
- Windows 10-et futtató VM mentése
- Bekapcsolt (nem leállított) VM-ek mentése
- Leállított, (deallocated) VM mentése
 

## **Demóvideó**  
Nézd meg a teljes tesztvideót itt: [Youtube video](https://www.youtube.com/watch?v=q13woBsS5Ig)  

## **Lépések a reprodukáláshoz**  
1. Hozz létre egy Recovery Services Vault-ot az Azure portálon.  
2. Állíts be egy Backup Policy-t.  
3. Válaszd ki a támogatott VMs példányokat, és engedélyezd a mentést.  
4. Indíts manuális mentést a működés ellenőrzéséhez.

