# BRFN-River-Valley-Zones
python jupyter notebook  to cumulatively sum AFLB for specified target based on priorities


# rva_balance.ipynb
contains one function to sum stands up to target based on sorted priorites
spatial file can be changed to another file type but must contain the following fields
    - Rec_Cat_short (string) mistakenly named from For_Rep, should contain 3 letter code ex. HPD
    - Details (string) with the value "River Valleys Protection Zone"
    - Rec_Cat (int)
    - SIFA_2 (int) modified age 

exports a geoparquet 


# example_shortfall.csv
and an example of the csv used to get the shortfall values in ha
