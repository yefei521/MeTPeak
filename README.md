# MeTPeak
# Forked Author : Ye Fei

This Forked project was used to install MeTPeak successfually.

When I install the PeTPeak using the command followed, same error apeared time and again whatever I changed the method.
So I forked the project in my hub followed the suggest in the requests of arlston/MeTPeak and add the new file in inst/doc/exomePeak-Overview.pdf .
If you met the same error, you could change the command installed ("remotes::install_github("yefei521/MeTPeak",build_manual = "--no-manual")") or forked this project in your github.

> remotes::install_github("arlston/MeTPeak",build_manual = "--no-manual")
---------------------------------------------------------------------------
Downloading GitHub repo arlston/MeTPeak@HEAD
These packages have more recent versions available.
It is recommended to update all of them.
Which would you like to update?

 1: All                                        
 2: CRAN packages only                         
 3: None                                       
 4: matrixStats (0.62.0    -> 0.63.0   ) [CRAN]
 5: RCurl       (1.98-1.8  -> 1.98-1.9 ) [CRAN]
 6: yaml        (2.3.5     -> 2.3.6    ) [CRAN]
 7: XML         (3.99-0.10 -> 3.99-0.13) [CRAN]
 8: bit         (4.0.4     -> 4.0.5    ) [CRAN]
 9: sys         (3.4       -> 3.4.1    ) [CRAN]
10: png         (0.1-7     -> 0.1-8    ) [CRAN]
11: vctrs       (0.5.0     -> 0.5.1    ) [CRAN]
12: stringi     (1.7.6     -> 1.7.8    ) [CRAN]
13: openssl     (2.0.3     -> 2.0.5    ) [CRAN]
14: jsonlite    (1.8.2     -> 1.8.3    ) [CRAN]
15: RSQLite     (2.2.17    -> 2.2.19   ) [CRAN]
16: digest      (0.6.29    -> 0.6.30   ) [CRAN]
17: stringr     (1.4.1     -> 1.5.0    ) [CRAN]

Enter one or more numbers, or an empty line to skip updates: 
v  checking for file 'C:\Users\小北\AppData\Local\Temp\Rtmpyg7AKq\remotes1b4a822fe12\arlston-MeTPeak-3eb3180/DESCRIPTION' (748ms)
-  preparing 'MeTPeak':
v  checking DESCRIPTION meta-information ...
E  checking vignette meta-information ... 
   Output(s) listed in 'build/vignette.rds' but not in package:
     'inst/doc/exomePeak-Overview.pdf'
   Run R CMD build without --no-build-vignettes to re-create
Error: Failed to install 'MeTPeak' from GitHub:
  ! System command 'Rcmd.exe' failed
-----------------------------------------------------------------------


> remotes::install_github("yefei521/MeTPeak",build_manual = "--no-manual")
----------------------------------------------------------------------------
Downloading GitHub repo yefei521/MeTPeak@HEAD
These packages have more recent versions available.
It is recommended to update all of them.
Which would you like to update?

 1: All                                        
 2: CRAN packages only                         
 3: None                                       
 4: matrixStats (0.62.0    -> 0.63.0   ) [CRAN]
 5: RCurl       (1.98-1.8  -> 1.98-1.9 ) [CRAN]
 6: yaml        (2.3.5     -> 2.3.6    ) [CRAN]
 7: XML         (3.99-0.10 -> 3.99-0.13) [CRAN]
 8: bit         (4.0.4     -> 4.0.5    ) [CRAN]
 9: sys         (3.4       -> 3.4.1    ) [CRAN]
10: png         (0.1-7     -> 0.1-8    ) [CRAN]
11: vctrs       (0.5.0     -> 0.5.1    ) [CRAN]
12: stringi     (1.7.6     -> 1.7.8    ) [CRAN]
13: openssl     (2.0.3     -> 2.0.5    ) [CRAN]
14: jsonlite    (1.8.2     -> 1.8.3    ) [CRAN]
15: RSQLite     (2.2.17    -> 2.2.19   ) [CRAN]
16: digest      (0.6.29    -> 0.6.30   ) [CRAN]
17: stringr     (1.4.1     -> 1.5.0    ) [CRAN]

Enter one or more numbers, or an empty line to skip updates: 
v  checking for file 'C:\Users\小北\AppData\Local\Temp\Rtmpyg7AKq\remotes1b4a8b9c6d3a\yefei521-MeTPeak-a93673b/DESCRIPTION' (691ms)
-  preparing 'MeTPeak':
v  checking DESCRIPTION meta-information ...
v  checking vignette meta-information ...
-  excluding invalid files
   Subdirectory 'R' contains invalid file names:
     'descript.ion'
   Warning in .write_description(db, ldpath) :
     没有这样带非ASCII数据的编码: 转换为ASCII 
-  checking for LF line-endings in source and make files and shell scripts
-  checking for empty or unneeded directories
-  building 'MeTPeak_1.0.0.tar.gz'
   
* installing *source* package 'MeTPeak' ...
** using staged installation
** R
** inst
** byte-compile and prepare package for lazy loading
There were 17 warnings (use warnings() to see them)
** help
*** installing help indices
  converting help for package 'MeTPeak'
    finding HTML links ... done
    MeTPeak-package                         html  
    MeTPeak                                 html  
REDIRECT:topic	 Previous alias or file overwritten by alias: G:/R-4.1.0/library/00LOCK-MeTPeak/00new/MeTPeak/help/MeTPeak.html
** building package indices
** testing if installed package can be loaded from temporary location
Warning: 程辑包'Rsamtools'是用R版本4.1.1 来建造的
Warning: 程辑包'GenomeInfoDb'是用R版本4.1.2 来建造的
Warning: 程辑包'BiocGenerics'是用R版本4.1.1 来建造的
Warning: 程辑包'S4Vectors'是用R版本4.1.3 来建造的
Warning: 程辑包'IRanges'是用R版本4.1.1 来建造的
Warning: 程辑包'GenomicRanges'是用R版本4.1.2 来建造的
Warning: 程辑包'Biostrings'是用R版本4.1.1 来建造的
Warning: 程辑包'XVector'是用R版本4.1.1 来建造的
Warning: 程辑包'GenomicFeatures'是用R版本4.1.2 来建造的
Warning: 程辑包'AnnotationDbi'是用R版本4.1.1 来建造的
Warning: 程辑包'Biobase'是用R版本4.1.1 来建造的
Warning in normalizePath(path.expand(path), winslash, mustWork) :
  path[1]="C:/Users/??/Documents": 文件名、目录名或卷标语法不正确。
Warning: 程辑包'rtracklayer'是用R版本4.1.1 来建造的
Warning: 程辑包'GenomicAlignments'是用R版本4.1.1 来建造的
Warning: 程辑包'SummarizedExperiment'是用R版本4.1.1 来建造的
Warning: 程辑包'MatrixGenerics'是用R版本4.1.1 来建造的
Warning: 程辑包'matrixStats'是用R版本4.1.3 来建造的
** testing if installed package can be loaded from final location
Warning: 程辑包'Rsamtools'是用R版本4.1.1 来建造的
Warning: 程辑包'GenomeInfoDb'是用R版本4.1.2 来建造的
Warning: 程辑包'BiocGenerics'是用R版本4.1.1 来建造的
Warning: 程辑包'S4Vectors'是用R版本4.1.3 来建造的
Warning: 程辑包'IRanges'是用R版本4.1.1 来建造的
Warning: 程辑包'GenomicRanges'是用R版本4.1.2 来建造的
Warning: 程辑包'Biostrings'是用R版本4.1.1 来建造的
Warning: 程辑包'XVector'是用R版本4.1.1 来建造的
Warning: 程辑包'GenomicFeatures'是用R版本4.1.2 来建造的
Warning: 程辑包'AnnotationDbi'是用R版本4.1.1 来建造的
Warning: 程辑包'Biobase'是用R版本4.1.1 来建造的
Warning in normalizePath(path.expand(path), winslash, mustWork) :
  path[1]="C:/Users/??/Documents": 文件名、目录名或卷标语法不正确。
Warning: 程辑包'rtracklayer'是用R版本4.1.1 来建造的
Warning: 程辑包'GenomicAlignments'是用R版本4.1.1 来建造的
Warning: 程辑包'SummarizedExperiment'是用R版本4.1.1 来建造的
Warning: 程辑包'MatrixGenerics'是用R版本4.1.1 来建造的
Warning: 程辑包'matrixStats'是用R版本4.1.3 来建造的
** testing if installed package keeps a record of temporary installation path
* DONE (MeTPeak)
-----------------------------------------------------------------------------
