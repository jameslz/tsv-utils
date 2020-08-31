
# tsv-utils: tools for manipulate tsv file.

Author: LEI ZHANG

current version： `version：0.0.1-r2`

### main commond line interface

    $ tsv-utils


    Usage:   tsv-utils <command> <arguments>
    Version: 0.0.1-r2
    
    Command:
          -- Combination
             agg            combinate multi-file.
             join           join tables with primery key.
             tsv2xlsx       convert (multi-)tsv file to Excel file.
    
          -- Numeric data frame
             rank           rank/merge for numeric table.
             abundance      calculate relative abundance for numeric table.
             norm           normalization with counts map and normalization
                            factor for numeric table.
             stand          standardization for numeric table.
             melt           merge values with bin table file.
             distribution   calculate bins feature distribution.
             trim           trim rows using cutoff.(sum operation).
             nfilter        filter using value with specied collum. op: >= | <= .
    
          -- Editing
             annotation     annotating specify collum with key/value(s) db.
             links          transform annotation with links map and definitions.
             associate      associate with links map.
             definition     adding definition collum with key/value(s) db.
             replace        replace specify collum elements with key/value(s) db.
             reorder        reorder rows by specify key in specify collum.
             subset         retrieve ids in/not in list file [row].
             subcolumn      retrieve ids in/not in list file [collum].
             collapse       collapse '\t' separator to specify delim.
             add_headline   add headline.
             groupline      add groupline.
             placehold      fill empty cell with specify STR.
             reshape        reshape and bin using map file.
    
          -- Matrix Operation
             transpose      matrix transpose.
             submatrix      submatrix by id.
             matrix2tab     binary format.
             matrix2melt    elements in submatrix using metadata.
    
          -- Summary
             cut            print selected parts of lines.
             bins           uniq/bin/summary.
             uniq           unique specify collum and counts.
             nlines         calculate lines of file.
             stats          calculate stats for selected collum.
             unpack         unpack the bins files.
    
          -- auxiliary utils.
             view             View text file, ignor comments and blank lines.
    
    Licenced:
    (c) 2018-2020 - LEI ZHANG
    Logic Informatics Co.,Ltd.
    zhanglei@logicinformatics.com
