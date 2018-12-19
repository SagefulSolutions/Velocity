(a*((b*c)/d)(e)
23.10*((5280*50)/3)(16)

a = cost of fiber cable per meter
b = feet of cable (default - one mile)
c = how many miles you are running cable
d = 3 is a constant that changes feet to meters
e = how many cables you need to run in pairs of 12
{
1   12
2   24
3   36
4   48
5   60
6   72
7   84
8   96
9   108
10  120
11  132
12  144
13  156
14  168
15  180
16  192
}


$32,524,800 to run 192 fibers 50 miles comes out to $650,496/mile or $123.2 per foot for backbone lines.
$40,656,000 to run 60 fibers 200 miles comes out to $203,280/mile or $38.5 per foot for backbone lines.
$40,656,000 to run 12 fibers 1000 miles comes out to $40,656/mile or $7.70 per foot for backbone lines.

$113,836,000 to run 1250 miles of cable over 25 years comes out to 

Equation: $113,836,000/25/12/45 shows 

We need 9,035 people paying $35/month to pay this project off within 30 years.

(A*B)*C/D

A=1.75 Gbps
B=7 backhaul links (14 radios)
C=1024 (Gbps->Mbps)
D=4 (# of wards or "regions" in the network receiving some of the bandwidth)
(1.75*7)*1024/4

4 regions, each region gets 3,136Mbps (392GBps) (62 endpoints   @ 50Mbps)
                                                (124 endpoints  @ 25Mbps) ** Would only happen in crowded neighborhoods, unless we can intercept the bandwidth from Citynet's antennas in one location and bandwidth shape it with pfSense/Nagios/etc to everywhere else)

https://store.ubnt.com/collections/wireless/products/airfiber-24hd
14 1.75Gbps radios @ $3,180 each (with 6% tax) = $44,520 over 4 years  = $11,130 per year, $927.50 per month or $231.88 per week.


https://www.amazon.com/NETGEAR-10-Gigabit-Multi-Gigabit-Rackmount-Multi-speed/dp/B01LXVJBXR/
4x (data link redundancy on each end of wireless bridge) 16 port 10Gbit switches @ $1,376.94 eac (with 6% tax) over 4 years  = $1,376.94/year, $114.75 per month or $28.69 per week.  

https://www.amazon.com/APC-Smart-UPS-2000VA-Tower-100-127V/dp/B00DQOAFH0/
4x (power redundancy on each end of link) @ $1250 each over 4 years = $1,250/yr, $104.17/mo or $26.04/wk
