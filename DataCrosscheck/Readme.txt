..######..########...#######...######...######...######..##.....##.########..######..##....##
.##....##.##.....##.##.....##.##....##.##....##.##....##.##.....##.##.......##....##.##...##.
.##.......##.....##.##.....##.##.......##.......##.......##.....##.##.......##.......##..##..
.##.......########..##.....##..######...######..##.......#########.######...##.......#####...
.##.......##...##...##.....##.......##.......##.##.......##.....##.##.......##.......##..##..
.##....##.##....##..##.....##.##....##.##....##.##....##.##.....##.##.......##....##.##...##.
..######..##.....##..#######...######...######...######..##.....##.########..######..##....##
                           .########.....###....########....###...
                           .##.....##...##.##......##......##.##..
                           .##.....##..##...##.....##.....##...##.
                           .##.....##.##.....##....##....##.....##
                           .##.....##.#########....##....#########
                           .##.....##.##.....##....##....##.....##
                           .########..##.....##....##....##.....##
              ------------------------ Ishfaq Ahmed ------------------------
              ---------------- Github: @IshfaqAhmedProg --------------------

Crosscheck files like txt,csv,gzip
   for gzip    --> Make sure the gzip contains json objects of the same length
   for csv,txt --> Make sure the file has headers on the first line
        
1. Make sure the data you want to crosscheck is in the input folder, and all the data in input 
   folder is of the same type.

2. Add your data to crosscheck in ref.xlsx and rename the header so that it matches with the 
   header of the data you want crosscheck in the input files 
    e.g.: If you want to check the party_cd in the input file then the header in ref.xlsx 
          should be party_cd, and below that add all the values you want to match.

3. Run the DataCrosscheck.exe and follow the steps.

4. You can split the data according to values in the input file. Just accept to split the data,
   and then select the header whose values you want to split by.
    e.g.: If you want to split according to county_desc then the data will be split according 
          to how many different kinds of data are in county_desc.

5. The output data will not contain the headers, you can choose to prepend the headers back to
   the output data once all the files have been crosschecked.
