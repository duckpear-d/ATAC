# ATAC
ATAC-analysis

1.ATAC_gene_avr_max.r
---------------------
Required: 
>R 

Usage:

+Rscript ATAC_gene_avr_max.r input_file region output_file    
	-input_file:the result provided by Chipseeker  
		*format(5 columns):"seqnames","start","V4","annotation","SYMBOL"  
		*V4 means the value of peaks  
	region:the region needed to be caculated  
		format:"promoter","genebody"  
	output_file:average and max value of genes  

