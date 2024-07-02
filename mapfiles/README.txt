These Natural Earth files were downloaded from https://github.com/nvkelso/natural-earth-vector/tree/master/10m_cultural
Version 5.1.2
The ne_10m_populated_places_trimmed files were produced by a custom script that trimmed the original ne_10m_populated_places dbf file to the following columns, drastically reducing the file size:
columns_to_keep = ['SCALERANK', 'FEATURECLA', 'NAME', 'NAMEASCII', 'SOV0NAME',	'SOV_A3',	'ADM0NAME', 'ADM0_A3',	'ADM1NAME', 'ISO_A2', 'POP_MAX', 'geometry']
