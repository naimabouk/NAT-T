# NAT-T
Nat description: we designed a topology simulating an access to a web server 
named server0 on internet by configuring a Nat (network adresses translation). 
The hosts on the private network (192.168.0.0/16) adresses are mapped to public adresses using address pool 201.50.9.0/28 
configured on the border router wich is connected to the ISP (internet service provider) router. 
To achieve this goal we have used both side, for the private network and for the ISP a Cisco 2911 ISR router.
