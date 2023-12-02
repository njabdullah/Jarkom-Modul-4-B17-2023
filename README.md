# Jarkom-Modul-4-B17-2023

## Anggota Kelompok
| Nama                       | NRP        |
| -------------------------- | ---------- |
| Abdullah Nasih Jasir       | 5025211111 |
| Yohanes Teguh Ukur Ginting | 5025211179 |

## Rute
| Subnet | Rute                                     | Jumlah IP | Netmask |
|--------|------------------------------------------|-----------|---------|
| A1     | Aura - Frieren                           | 2         | /30     |
| A2     | Frieren - Switch3 - LakeKorridor         | 25        | /27     |
| A3     | Frieren - Flamme                         | 2         | /30     |
| A4     | Flamme - Fern                            | 2         | /30     |
| A5     | Fern - Switch4 - LaubHills - AppetitRegion| 1023     | /21     |
| A6     | Flamme - Switch5 - RohrRoad              | 1001      | /22     |
| A7     | Flamme - Himmel                          | 2         | /30     |
| A8     | Himmel - Switch6 - SchwerMountains       | 6         | /29     |
| A9     | Aura - Eisen                             | 2         | /30     |
| A10    | Eisen - Switch1 - Richter - Revolte      | 3         | /29     |
| A11    | Eisen - Linie                            | 2         | /30     |
| A12    | Linie - Lawine                           | 2         | /30     |
| A13    | Lawine - Switch7 - BredtRegion - Heiter  | 31        | /26     |
| A15    | Heiter - Switch8 - RiegelCanyon - Sein   | 512       | /22     |
| A16    | Linie - Switch11 - GranzChannel          | 255       | /23     |
| A17    | Eisen - Lugner                           | 2         | /30     |
| A18    | Lugner - Switch10 - TurkRegion           | 1001      | /22     |
| A19    | Lugner - Switch9 - GlobeForest           | 251       | /24     |
| A20    | Eisen - Switch0 - Stark                  | 2         | /30     |
| A21    | Aura - Denken                            | 2         | /30     |
| A22    | Denken - Switch2 - RoyalCapital - WileRegion | 127   | /24     |
| Total  |                                          | 4255      | /19     |

---

## VLSM - CPT
### Pembagiaan Subnet
![Test2](https://github.com/njabdullah/Jarkom-Modul-4-B17-2023/assets/92930757/dd97e202-90e2-4fe8-bab7-ec9661596059)

### Tree VLSM
![image](https://github.com/njabdullah/Jarkom-Modul-4-B17-2023/assets/92930757/609d5c37-df28-48ef-88f2-ec09396185f6)

### Pembagian NID, Netmask, dan Broadcast tiap Subnet
| Subnet | Network ID    | Netmask            | Broadcast      | Jumlah IP | Netmask |
|--------|---------------|--------------------|----------------|-----------|---------|
| A1     | 10.17.24.112  | 255.255.255.252    | 10.17.24.115   | 2         | /30     |
| A2     | 10.17.24.64   | 255.255.255.224    | 10.17.24.95    | 25        | /27     |
| A3     | 10.17.24.116  | 255.255.255.252    | 10.17.24.119   | 2         | /30     |
| A4     | 10.17.24.120  | 255.255.255.252    | 10.17.24.123   | 2         | /30     |
| A5     | 10.17.0.0     | 255.255.248.0      | 10.17.7.255    | 1023      | /21     |
| A6     | 10.17.8.0     | 255.255.252.0      | 10.17.11.255   | 1001      | /22     |
| A7     | 10.17.24.124  | 255.255.255.252    | 10.17.24.127   | 2         | /30     |
| A8     | 10.17.24.96   | 255.255.255.248    | 10.17.24.103   | 6         | /29     |
| A9     | 10.17.24.128  | 255.255.255.252    | 10.17.24.131   | 2         | /30     |
| A10    | 10.17.24.104  | 255.255.255.248    | 10.17.24.111   | 3         | /29     |
| A11    | 10.17.24.132  | 255.255.255.252    | 10.17.24.135   | 2         | /30     |
| A12    | 10.17.24.136  | 255.255.255.252    | 10.17.24.139   | 2         | /30     |
| A13    | 10.17.24.0    | 255.255.255.192    | 10.17.24.63    | 31        | /26     |
| A15    | 10.17.16.0    | 255.255.252.0      | 10.17.19.255   | 512       | /22     |
| A16    | 10.17.20.0    | 255.255.254.0      | 10.17.21.255   | 255       | /23     |
| A17    | 10.17.24.140  | 255.255.255.252    | 10.17.24.143   | 2         | /30     |
| A18    | 10.17.12.0    | 255.255.252.0      | 10.17.15.255   | 1001      | /22     |
| A19    | 10.17.22.0    | 255.255.255.0      | 10.17.22.255   | 251       | /24     |
| A20    | 10.17.24.144  | 255.255.255.252    | 10.17.24.147   | 2         | /30     |
| A21    | 10.17.24.148  | 255.255.255.252    | 10.17.24.151   | 2         | /30     |
| A22    | 10.17.23.0    | 255.255.255.0      | 10.17.23.255   | 127       | /24     |

### Hasil Pembagian IP tiap Node
IP ini yang akan digunakan untuk subnetting
| Subnet | Node           | IP            |
|--------|----------------|---------------|
| A1     | Aura           | 10.17.24.113  |
| A1     | Frieren        | 10.17.24.114  |
| A2     | Frieren        | 10.17.24.65   |
| A2     | LakeKoridor    | 10.17.24.66   |
| A3     | Frieren        | 10.17.24.117  |
| A3     | Flamme         | 10.17.24.118  |
| A4     | Flamme         | 10.17.24.121  |
| A4     | Fern           | 10.17.24.122  |
| A5     | Fern           | 10.17.0.1     |
| A5     | AppetitRegion  | 10.17.0.2     |
| A5     | LaubHills      | 10.17.2.115   |
| A6     | Flamme         | 10.17.8.1     |
| A6     | RohrRoad       | 10.17.8.2     |
| A7     | Flamme         | 10.17.24.125  |
| A7     | Himmel         | 10.17.24.126  |
| A8     | Himmel         | 10.17.24.97   |
| A8     | SchwerMountains| 10.17.24.98   |
| A9     | Aura           | 10.17.24.129  |
| A9     | Eisen          | 10.17.24.130  |
| A10    | Eisen          | 10.17.24.105  |
| A10    | Richter        | 10.17.24.106  |
| A10    | Revolte        | 10.17.24.107  |
| A11    | Eisen          | 10.17.24.133  |
| A11    | Linie          | 10.17.24.134  |
| A12    | Linie          | 10.17.24.137  |
| A12    | Lawine         | 10.17.24.138  |
| A13    | Lawine         | 10.17.24.1    |
| A13    | Heiter         | 10.17.24.2    |
| A13    | BredtRegion    | 10.17.24.3    |
| A15    | Haiter         | 10.17.16.1    |
| A15    | RiegelCanyon   | 10.17.16.2    |
| A15    | Sein           | 10.17.18.0    |
| A16    | Linie          | 10.17.20.1    |
| A16    | GranzChannel   | 10.17.20.2    |
| A17    | Eisen          | 10.17.24.141  |
| A17    | Lugner         | 10.17.24.142  |
| A18    | Lugner         | 10.17.12.1    |
| A18    | TurkRegion     | 10.17.12.2    |
| A19    | Lugner         | 10.17.22.1    |
| A19    | GrobeForest    | 10.17.22.2    |
| A20    | Eisen          | 10.17.24.145  |
| A20    | Stark          | 10.17.24.146  |
| A21    | Aura           | 10.17.24.149  |
| A21    | Denken         | 10.17.24.150  |
| A22    | Denken         | 10.17.23.1    |
| A22    | RoyalCapital   | 10.17.23.2    |
| A22    | WilleRegion    | 10.17.23.65   |

### Routing
Routing dilakukan pada Router (terdapat 11 router)

Aura<br>
![image](https://github.com/njabdullah/Jarkom-Modul-4-B17-2023/assets/92930757/e22ad33c-c228-4bef-8421-8d9cdc1901ff)
![image](https://github.com/njabdullah/Jarkom-Modul-4-B17-2023/assets/92930757/e8f91daf-b593-4dae-9b23-293562c7377e)

Denken<br>
![image](https://github.com/njabdullah/Jarkom-Modul-4-B17-2023/assets/92930757/0d1b66a8-b5ba-4daf-94de-6c234571d030)

Frieren<br>
![image](https://github.com/njabdullah/Jarkom-Modul-4-B17-2023/assets/92930757/31b1bb44-ce1e-46fe-aa03-f5c4235c61a7)

Flamme<br>
![image](https://github.com/njabdullah/Jarkom-Modul-4-B17-2023/assets/92930757/62727c27-3976-4f8e-a294-73d27ce6a14f)

Fern<br>
![image](https://github.com/njabdullah/Jarkom-Modul-4-B17-2023/assets/92930757/63b9f20f-2f8f-44e9-b555-f3340652c00a)

Himmel<br>
![image](https://github.com/njabdullah/Jarkom-Modul-4-B17-2023/assets/92930757/c1af556d-f073-48ab-817b-830a1e2cf234)

Eisen<br>
![image](https://github.com/njabdullah/Jarkom-Modul-4-B17-2023/assets/92930757/83427bfb-53be-4e4d-aa52-8941b30821a5)

Lugner<br>
![image](https://github.com/njabdullah/Jarkom-Modul-4-B17-2023/assets/92930757/66f4c2f9-f1af-4b7d-a062-c88c5b273a28)

Linie<br>
![image](https://github.com/njabdullah/Jarkom-Modul-4-B17-2023/assets/92930757/4e240f76-7c21-47b2-afd2-f2405e47f101)

Lawine<br>
![image](https://github.com/njabdullah/Jarkom-Modul-4-B17-2023/assets/92930757/15dd23eb-9dc5-46ce-97ec-327b3c254bdf)

Heiter<br>
![image](https://github.com/njabdullah/Jarkom-Modul-4-B17-2023/assets/92930757/1719da06-6abe-4a49-9993-36b5085e53fe)

