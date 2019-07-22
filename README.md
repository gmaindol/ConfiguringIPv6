# Configuring IPv6
Configuring IPv6 in PANOS 
IPv6 Interface configuration skillet provides quick an easy way to configure an IPv6 address on PANOS data plane interfaces. It configured followig on the interface 
1) Enables IPv6 on the interface
2) IPv6 address 
3) Virtual Router
4) Security Zone
5)Enables NDP monitoring

You can provides subnet or host IP. When using subnet the host part of the address is derived using the Interface ID. RA are not enabled and needs to configured seperately.


# Support Policy
The code and templates in the repo are released under an as-is, best effort, support policy. These scripts should be seen as community supported and Palo Alto Networks will contribute our expertise as and when possible. We do not provide technical support or help in using or troubleshooting the components of the project through our normal support options such as Palo Alto Networks support teams, or ASC (Authorized Support Centers) partners and backline support options. The underlying product used (the VM-Series firewall) by the scripts or templates are still supported, but the support is only for the product functionality and not for help in deploying or using the template or script itself. Unless explicitly tagged, all projects or work posted in our GitHub repository (at https://github.com/PaloAltoNetworks) or sites other than our official Downloads page on https://support.paloaltonetworks.com are provided under the best effort policy.