# Jarkom-Modul-4-B11-2023

| No | Nama | NRP |
| -------- | -------- | -------- |
| 1 | Muhammad Rafif Tri Risqullah | 5025211009 |
| 2 | Ulima Kaltsum Rizky Hibatullah | 5025211232 |

Pembagian Node Awal

![Subnet VLSM-1](https://github.com/ulimakrh/Jarkom-Modul-4-B11-2023/assets/114993076/55fe77da-9651-477c-afe8-1fe9285e716f)

1. VLSM - GNS3

Route

![image](https://github.com/ulimakrh/Jarkom-Modul-4-B11-2023/assets/114993076/c381705c-2038-4785-ae25-471807d856a8)

Tree

![Subnet VLSM-2](https://github.com/ulimakrh/Jarkom-Modul-4-B11-2023/assets/114993076/813f19fc-6e4f-4bc4-a5c6-541e35f34ee8)

Pembagian IP

![image](https://github.com/ulimakrh/Jarkom-Modul-4-B11-2023/assets/114993076/6eb5f02e-f3e5-4420-93d2-05f44d2aafd2)


Konfigurasi GNS3
- Aura
```
Aura
auto eth0
iface eth0 inet dhcp

auto eth1
iface eth1 inet static
	address 10.14.0.25
	netmask 255.255.255.252

auto eth2
iface eth2 inet static
	address 10.14.0.21
	netmask 255.255.255.252

auto eth3
iface eth3 inet static
	address 10.14.0.41
	netmask 255.255.255.252
```
- Heiter
```
Heiter

auto eth0
iface eth0 inet static
	address 10.14.0.67
	netmask 255.255.255.192
	gateway 10.14.0.65

auto eth1
iface eth1 inet static
	address 10.14.4.1
	netmask 255.255.252.0
```
- Riegel Canyon
```
RiegelCanyon

auto eth0
iface eth0 inet static
	address 10.14.4.2
	netmask 255.255.252.0
	gateway 10.14.4.1
```
- Sein
```
Sein

auto eth0
iface eth0 inet static
	address 10.14.4.3
	netmask 255.255.252.0
	gateway 10.14.4.1
```
- Lawine
```
Lawine

auto eth0
iface eth0 inet static
	address 10.14.0.2
	netmask 255.255.255.252
	gateway 10.14.0.1

auto eth1
iface eth1 inet static
	address 10.14.0.65
	netmask 255.255.255.192
```
- BredtRegion
```
BredtRegion

auto eth0
iface eth0 inet static
	address 10.14.0.66
	netmask 255.255.255.192
	gateway 10.14.0.65
```
- Linie
```
Linie 

auto eth0
iface eth0 inet static
	address 10.14.0.6
	netmask 255.255.255.252
	gateway 10.14.0.5


auto eth1
iface eth1 inet static
	address 10.14.0.1
	netmask 255.255.255.252

auto eth2
iface eth2 inet static
	address 10.14.1.1
	netmask 255.255.254.0
```
- GranzChannel
```
GranzChannel

auto eth0
iface eth0 inet static
	address 10.14.1.2
	netmask 255.255.254.0
	gateway 10.14.1.1
```
- Eisen
```
Eisen

auto eth0
iface eth0 inet static
	address 10.14.0.22
	netmask 255.255.255.252
	gateway 10.14.0.20

auto eth1
iface eth1 inet static
	address 10.14.0.9
	netmask 255.255.255.248

auto eth2
iface eth2 inet static
	address 10.14.0.5
	netmask 255.255.255.252

auto eth3
iface eth3 inet static
	address 10.14.0.13
	netmask 255.255.255.252

auto eth4
iface eth4 inet static
	address 10.14.0.17
	netmask 255.255.255.252
```
- Richter
```
Richter

auto eth0
iface eth0 inet static
	address 10.14.0.10
	netmask 255.255.255.248
	gateway 10.14.0.9
```
- Revolte
```
Revolte

auto eth0
iface eth0 inet static
	address 10.14.0.11
	netmask 255.255.255.248
	gateway 10.14.0.9
```
- Lugner
```
Lugner

auto eth0
iface eth0 inet static
	address 10.14.0.14
	netmask 255.255.255.252
	gateway 10.14.0.13

auto eth1
iface eth1 inet static
	address 10.14.2.1
	netmask 255.255.255.0

auto eth2
iface eth2 inet static
	address 10.14.8.1
	netmask 255.255.252.0
```
- TurkRegion
```
TurkRegion

auto eth0
iface eth0 inet static
	address 10.14.8.2
	netmask 255.255.252.0
	gateway 10.14.8.1
```
- GrobeForest
```
GrobeForest

auto eth0
iface eth0 inet static
	address 10.14.2.2
	netmask 255.255.255.0
	gateway 10.14.2.1
```
- Stark
```
Stark

auto eth0
iface eth0 inet static
	address 10.14.0.18
	netmask 255.255.255.252
	gateway 10.14.0.17
```
- Frieren
```
Frieren

auto eth0
iface eth0 inet static
	address 10.14.0.26
	netmask 255.255.255.252
	gateway 10.14.0.25

auto eth1
iface eth1 inet static
	address 10.14.0.29
	netmask 255.255.255.252

auto eth2
iface eth2 inet static
	address 10.14.0.129
	netmask 255.255.255.224
```
- LakeKorridor
```
LakeKorridor

auto eth0
iface eth0 inet static
	address 10.14.0.130
	netmask 255.255.255.224
	gateway 10.14.0.129
```
- Flamme
```
Flamme

auto eth0
iface eth0 inet static
	address 10.14.0.30
	netmask 255.255.255.252
	gateway 10.14.0.29

auto eth1
iface eth1 inet static
	address 10.14.0.37
	netmask 255.255.255.252

auto eth2
iface eth2 inet static
	address 10.14.16.1
	netmask 255.255.252.0

auto eth3
iface eth3 inet static
	address 10.14.0.33
	netmask 255.255.255.252
```
- Himmel
```
Himmel

auto eth0
iface eth0 inet static
	address 10.14.0.34
	netmask 255.255.255.252
	gateway 10.14.0.33

auto eth1
iface eth1 inet static
	address 10.14.0.49
	netmask 255.255.255.248
```
- SchwerMountains
```
SchwerMountains

auto eth0
iface eth0 inet static
	address 10.14.0.50
	netmask 255.255.255.248
	gateway 10.14.0.49
```
- RohrRoad
```
RohrRoad

auto eth0
iface eth0 inet static
	address 10.14.16.2
	netmask 255.255.252.0
	gateway 10.14.16.1
```
- Fern
```
Fern

auto eth0
iface eth0 inet static
	address 10.14.0.38
	netmask 255.255.255.252
	gateway 10.14.0.37

auto eth1
iface eth1 inet static
	address 10.14.20.1
	netmask 255.255.248.0
```
- LaubHills
```
LaubHills

auto eth0
iface eth0 inet static
	address 10.14.20.2
	netmask 255.255.248.0
	gateway 10.14.20.1
```
- AppetitRegion
```
Appetit Region

auto eth0
iface eth0 inet static
	address 10.14.20.3
	netmask 255.255.248.0
	gateway 10.14.20.1
```
- Denken
```
Denken

auto eth0
iface eth0 inet static
	address 10.14.0.42
	netmask 255.255.255.252
	gateway 10.14.0.41

auto eth1
iface eth1 inet static
	address 10.14.0.129
	netmask 255.255.255.0
```
- RoyalCapital
```
RoyalCapital

auto eth0
iface eth0 inet static
	address 10.14.0.130
	netmask 255.255.255.0
	gateway 10.14.0.129
```
- WilleRegion
```
WillieRegion

auto eth0
iface eth0 inet static
	address 10.14.0.131
	netmask 255.255.255.0
	gateway 10.14.0.129
```

2. CIDR - Cisco Packet Tracet (CPT)
