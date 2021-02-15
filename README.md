# new-vps
vps

    "name": "as",
    "id": "/subscriptions/edcfd4b9-7d19-4f09-9a76-50159ea936ed/resourceGroups/as/providers/Microsoft.Compute/virtualMachines/as",
    "type": "Microsoft.Compute/virtualMachines",
    "location": "southeastasia",
    "properties": {
        "vmId": "816d404f-a403-4ca9-a66a-187a8c6c6b41",
        "hardwareProfile": {
            "vmSize": "Standard_B2s"
        },
        "storageProfile": {
            "imageReference": {
                "publisher": "Canonical",
                "offer": "UbuntuServer",
                "sku": "18.04-LTS",
                "version": "latest"
            },
            "osDisk": {
                "osType": "Linux",
                "name": "as_disk1_92fb2af6b04c49ce8ee2e27e8e1df5e6",
                "createOption": "FromImage",
                "caching": "ReadWrite",
                "managedDisk": {
                    "storageAccountType": "Premium_LRS",
                    "id": "/subscriptions/edcfd4b9-7d19-4f09-9a76-50159ea936ed/resourceGroups/as/providers/Microsoft.Compute/disks/as_disk1_92fb2af6b04c49ce8ee2e27e8e1df5e6"
                },
                "diskSizeGB": 30
            },
            "dataDisks": []
        },
        "osProfile": {
            "computerName": "as",
            "adminUsername": "vps",
            "linuxConfiguration": {
                "disablePasswordAuthentication": true,
                "ssh": {
                    "publicKeys": [
                        {
                            "path": "/home/vps/.ssh/authorized_keys",
                            "keyData": "ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABgQDbONzQVv0dlRhqrNUuUZ2nk66z\r\nt72PYgojUw3hRZ4bmbjW1iM0UicjAZ7e9QWvA10XAh0f9ZIVwpeMHEQppeKTN41r\r\nKVW0d52DEtYU23IBM1Jm5emDOuUzxDyG5vHlKjLNrCcZz/Q7eJd1jNAykTFYKEi1\r\nQ9yMmG/DnXXfKWCTiRs2ZhUUIDuL+WYdTgqucDhJA7/VjBH7DRR63bS+QHhkkrGC\r\nTX3NBfL050rIsM/tcL9KHVT9n8LUmdpQyZgS1fhXCHlpYccCP2PZ4cqr0qOFI9js\r\nPmjymiqsGQbsiCa3IKFdNhOBjk2rxKFArs43vli4gpINYhZwJtLSUCH7miQMAR5H\r\nkPniC4y+XBGxWQsDzacrzhlB9jDt1NUD4bbcP9AZwcfNvV1Tr+nB8apqOPrBiSwf\r\nu4A63b1lEWsghetMDTc4HsCMx+6in1x+MLpLXAzVAfFcyy9I89a0PQGNh4FaWxn5\r\nwwaI4ALlSE95Khsj0Om7DO1n07TJcdZnOKgTOX0= generated-by-azure\r\n"
                        }
                    ]
                }
            },
            "secrets": []
        },
        "networkProfile": {
            "networkInterfaces": [
                {
                    "id": "/subscriptions/edcfd4b9-7d19-4f09-9a76-50159ea936ed/resourceGroups/as/providers/Microsoft.Network/networkInterfaces/as890"
                }
            ]
        },
        "diagnosticsProfile": {
            "bootDiagnostics": {
                "enabled": true
            }
        },
        "provisioningState": "Succeeded"
    }
