# OC17wc_deepauto_06152026
R notebooks and csvs used in Salcedo et al. assessing dark carbon fixation throughout the deep northeastern pacific

OC17_contig_tax_abundance_06152026_public.rmd 
  Uses information in revision_eukaryotic_scaffolds_1000bp.csv and revision_scaffold_taxonomy_2500bp.csv to generate figure S2 and assess the
  relative abundance of contigs encoding genes involved in DIC fixation pathways across the transect, grouped by taxonomy as ID'd by gtdb v207

OC17_genewise_analysis_06152026_public.rmd
  Outlines going from assemblies to annotations and eventually production of Fig. 1 and Table 1. Produces all_sites.csv, transect_KOdf.csv,
  and transect_pathwaydf.csv and uses bitscore_thresholds.csv and CAT_gene_lengths.csv. 
    
OC17_geochemistry_cor_06152026.rmd
  Uses the relative abundances generated in OC17_genewise_analysis_06152026_public.rmd to assess for statistically significant correlations 
  between gene abundance and geochemical parameters of the water column. Uses arandia-gorostidi_etal_isme_supptables_urea_tableS1.csv and 
  produces table S2, 3, 4, and 5 in manuscript. 
    
OC17_refinedMAG_abundance_heatmap_06152026_public.Rmd
  Displays the relative abundance of each genome included in the study throughout the water column, grouped by taxonomic phyla and which
  pathway they encode. produces figure SX and uses supplementary tables S7 and S9. 
    
OC17_refinedMAG_annotation_06152026_public.rmd
  Outlines the processing of refined genomes to generate annotations, taxonomic ID, and relative abundance. produces 
  refined_auto_MAGs_edited_06152026.csv which is used for most downstream figure creation. Also produces tables S6 and S10. Uses refined genome
  files and DRAM_energy_pathways_v5.tsv.
  
OC17_refinedMAG_cat_abundance_fig3_06152026_public.rmd
  Code used to process refined_auto_MAGs_edited_06152026.csv and produce figure 3.
  
OC17_refinedMAG_cat_potential_fig4_06152026_public.rmd
  Code used to process refined_auto_MAGs_edited_06152026.csv and produce figure 4.

OC17_refinedMAG_gene_tree_06152026.rmd
  Code used to create phylogenetic trees to confirm automatic annotations of amo/pmo and nxr/nar. produces 06152026_genetree_to_remove.csv 
  which is used to finally generate refined_auto_MAGs_edited_06152026.csv in OC17_refinedMAG_cat_abundance_fig3_06152026_public.rmd. 
  
OC17_refinedMAG_OMtransporters_06152026_public.rmd
  Code similar to that in OC17_refinedMAG_cat_potential_fig4_06152026_public.rmd and used to assess the presence of ABC transporters and DIC
  pathway completion across genomes included in study. used to produce figures S4. Uses DRAM_completeauto_OM_pathway.csv

OC17_refinedMAG_sulfiteoxidation2genes_06152026_public.Rmd
  Code similar to that in OC17_refinedMAG_cat_potential_fig4_06152026_public.rmd and used to assess the presence of sulfite oxidation genes
  across genomes included in the study. used to generate figure S5.

OC17_refinedMAG_tax_abundance_fig2_06152026_public.Rmd
  Code used to generate figure 2 panels A and B and assess the relative abundance of genomes assessed in the study by taxonomic lineage. Uses 
  table S6, S9, and catabolism_MAGs_06152026.csv to generate figure 2 and table 2. 

OC17_refinedMAG_tax_abundance_figS3_06152026_public.rmd
  Similar to code in OC17_refinedMAG_tax_abundance_fig2_06152026_public.Rmd but assesses all phyla at the family level classification. Uses 
  table S6, S9, and catabolism_MAGs_06152026.csv to produce figure S3.

OC17_contigs_v_assembly_mapping_plotting_06152026.rmd
  Plots the data in 06152026_genomevassembly_mapping_info.tsv to generate figure S1. 
