# CreateAnyVMAzure
az cli script that will run you from publisher to version to create a new VM

This script will help you quickly create a VM 

It will ask you: 
Resource group name
location
admin name 
password
publisher (then list skus based on publisher
sku ( then list versions based on sku)
versions

Then it creates a VM sized at Standard_DS2 and a 128Gb OS disk.
If you don't like these defaults, you can change the script.

The best way to use this is run it from Cloudshell.
