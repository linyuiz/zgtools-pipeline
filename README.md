# zgtools流程
待更新示例结果文件，要求作图与结果均达到CNS水平

欢迎交流，需要代做分析（擅长T2T）可联系 QQ：1954616586

模块：

           #Survey【基因组-Survey】
           * — — — — — — — — — — — — — — — — — — — — — — — — — — *
           | survey                --Survey Pipeline             |
           | nt                    --NT Blast                    |
           * — — — — — — — — — — — — — — — — — — — — — — — — — — *

           #Assembly【基因组-组装与纠错】
           * — — — — — — — — — — — — — — — — — — — — — — — — — — *
           | methods               --Assembler List              |
           | hifiasm               --Hifiasm Assemble            |
           | n50plot               --N50 & Contig Length Plot    |
           | polish                --Normal Polish(Racon+Pilon)  |
           | nextpolish2           --T2T Polish(Nextpolish2)     |
           | purge                 --Purge Dups                  |
           * — — — — — — — — — — — — — — — — — — — — — — — — — — *

           #Assessment【基因组-评估】      
           * — — — — — — — — — — — — — — — — — — — — — — — — — — *
           | mappingdata           --Mapping Assessment          |
           | qv                    --QV Assessment               |
           | BUSCO                 --BUSCO Assessment            |
           | LAI                   --LAI Assessment              |
           | CRAQ                  --CRAQ Assessment             |
           | omark[Update]         --OMArk Assessment            |
           | compleasm[Update]     --Compleasm Assessment        |
           * — — — — — — — — — — — — — — — — — — — — — — — — — — *

           #HiC & Syntenic【基因组-HIC挂载与共线性】    
           * — — — — — — — — — — — — — — — — — — — — — — — — — — *
           | hicup_nt              --HiCUP Truncater + NT Blast  |
           | haphic                --HapHiC Scaffolding Pipeline |
           | hicup                 --HiCUP Assessment            |
           | makechr               --Make Chr Level Genome       |
           | hicplot               --HiC Plot Pipeline           |
           | ragtag                --RagTag Anchor Ref Genome    |
           | syntenic              --Mummer4 Align And Plot      |
           | syri                  --Mummer4 Align + Syri        |  
           | align                 --Genome Align + Use dotPloty |
           | subphaser             --SubPhaser Phase Subgenomes  |
           * — — — — — — — — — — — — — — — — — — — — — — — — — — *


           #Evolution【基因组-进化分析】       
           * — — — — — — — — — — — — — — — — — — — — — — — — — — *
           | dupgene[Update]       --Find DupGene + Whisker Plot |
           | genetribe             --Allele Gene Identification  |
           * — — — — — — — — — — — — — — — — — — — — — — — — — — *

           #T2T【基因组-T2T组装与分析】   
           * — — — — — — — — — — — — — — — — — — — — — — — — — — *
           | homotools             --T2T Tools                   |
           | genomeview            --Genomeview                  |
           | telomere              --Telomere Count              |
           | centromere            --Centromere Identification   |
           * — — — — — — — — — — — — — — — — — — — — — — — — — — *

           #Others【杂项】
           * — — — — — — — — — — — — — — — — — — — — — — — — — — *
           | n50                   --N50 Stat                    |
           | centromere            --Centromere Identification   |
           | getpep                --Deal With Genome And GFF3   |
           | longest_trans         --Get Longest Transcript      |
           | filter_assembly       --Filter .assembly            |
           | env                   --Check Tools Env             |
           | qtask                 --Check Sge Tasks             |
           | sqstat                --Check Slurm Tasks           |
           | tips                  --Some Little Commands        |
           * — — — — — — — — — — — — — — — — — — — — — — — — — — *

