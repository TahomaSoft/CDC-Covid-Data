# Case Surveillance Data from CDC #

Because these files are so large (1.6 GB; 13*10^6 lines of data and
increasing) these files are being split and then compressed using XZ
compression to avoid warnings and errors on GitHub.

To restore to the original state, on Linux/Unix do something like the following command-line sequence:

xz -d *.xz

cat *.csv.part1 *.csv.part2 *.csv.part3 > COVID-19_Case_Surveillance_Public_Use_Data.csv
