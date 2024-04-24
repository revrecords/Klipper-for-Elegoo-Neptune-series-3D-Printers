# 0. Introduction
# 1. PLA and General
# 2. PETG
PETG must be printed slower than PLA.
  It often strings more - doubling retraction distance, increasing retraction speed, and reducing temperature are all possibilities.
  As a last resort, play around with Z-hop.
  
# 3. ABS
Generally, ABS should be printed inside an Enclosure.
  ABS has a very high glass transition temp of 105C, and thus a very high print temperature - very far above ambient.
  The temperature differential between print and ambient makes it very prone to warping.
## 3a. With an Enclosure
With an enclosure, the ambient temperature rises, reducing the differential with print temperature.
  This improves the stability of ABS - and allows higher print temps.
  With an enclosure, it becomes possible to use the recommended 110/110 bed and 260/240 nozzle temperature, and not care too much about extrusion rate.
## 3b. Without an Enclosure
Without an enclosure, the differential between ambient and print can be massive, making ABS less stable. Build height is therefore limited.
  Things like extrusion rate need to be carefully tuned, and even the bed and nozzle temps need to be carefully tuned.
  With stock thermal components, I have found success with 109/107 bed and 235/215 nozzle temperature, at least with xmm build height.
# 4. Flexibles
# 5. Exotic Materials
