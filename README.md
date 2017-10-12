# tabtk_xlsx

interface:

    $ tabtk_xlsx
    Usage: tabtk_xlsx  <xlsx> <sheet:file_path> [<sheet:file_path>]
    version: 0.0.1
 
 benchmark and usage:
 
    $time  tabtk_xlsx.py  ncbi.map.xlsx  ncbi:ncbi.map
    real    2m47.532s
    user    2m46.537s
    sys     0m0.829s
    
    $time  tabtk_xlsx  ncbi.map.xlsx  ncbi:ncbi.map
    real    0m12.577s
    user    0m11.980s
    sys     0m0.582s
  
    tabtk_xlsx  taxonomy.xlsx  phylum:phylum.txt order:order.txt  genus:genus.txt species:species.txt
