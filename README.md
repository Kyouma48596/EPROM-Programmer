# EPROM-Programmer
A microprocessor based EPROM programmer to program the 2716

The EPROM can be programmed by applying 25V at VPP and 5V at OE pin. Initially all data of EPROM will be 1’s and the user should make the bits zero selectively. Before the EPROM location is programmed it must be checked for whether it is empty (data in location must be FFH if the location is empty) The 8- bit parallel data is applied to the data pins of EPROM. The address for the EPROM is to be provided. To program the address of each location to be programmed should be stable for 55ms.When address and data are stable, a 50ms active high pulse is applied to CE input. 
