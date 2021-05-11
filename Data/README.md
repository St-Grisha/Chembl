## Data
***df_v2.csv*** - last modified table


**_ H** - all parmeters for hydrogenium analogs


*'molregno'* - ID in Chembl

*'canonical_smiles', 'Smiles_H'* - SMILES  

*'count_F'* - count F-atoms

*'activity_id'* - ID of experiment in Chembl 

*'assay_id'* - ID experiments series in Chembl  

*'doc_id_x'* - article ID  

*'record_id'* - ID of experiment in Chembl

*'standard_relation'* - determination accuracy 

*'standard_value'* - value of constants 

*'standard_units'* - unit of constants

*'standard_flag'* - dont know 

*'standard_type'* - type of constants (IC50)

*'description'* - text description of experiment

*'assay_type'* - https://chembl.gitbook.io/chembl-interface-documentation/frequently-asked-questions/general-questions#what-is-the-assay-type (necessity to drop?)

*'assay_test_type'* - in vitro or NA

*'assay_category'* - drop

*'assay_organism'* - organism ID in Chembl 

*'assay_tax_id'* - also

*'assay_strain'* - you know

*'assay_tissue'* - tissue type ID in Chembl for experiment

*'assay_cell_type'* - cell type ID in Chembl for experiment (drop if not na)

*'assay_subcellular_fraction'* - you know

*'tid'* - intermediate data (drop)

*'relationship_type'* - https://chembl.gitbook.io/chembl-interface-documentation/frequently-asked-questions/chembl-data-questions#what-does-the-target-relationship_type-flag-mean

*'confidence_score'* - https://chembl.gitbook.io/chembl-interface-documentation/frequently-asked-questions/chembl-data-questions#what-is-the-confidence-score

*'curated_by'* - data correctness curator

*'src_id'* - type of documents (https://www.ebi.ac.uk/chembl/api/data/source)

*'src_assay_id'* - also 

*'chembl_id'* - ...

*'cell_id'* - ID cell in Chembl

*'bao_format'* - the type of experiment

*'tissue_id'* - ID tissue in Chembl

*'variant_id'* - variant of experiments

*'aidx'* - important to know, what is it 

*'component_id'* - intermediate data (drop)

*'targcomp_id'* - intermediate data (drop)

*'homologue'* - drop and clean copyes in df (?) 

*'protein_class_id'* - intermediate data; ID of protein

*'comp_class_id'* - intermediate data (drop)

*'class_level'* - target protein class 

***'res'*** - **ratio of constants values for fluorinated and hydrohenated compounds** 

*'mw_freebase'* - molecular weight 

*'alogp'* - lipophility index 

*'hba'* -  count of H-bonds acceptor

*'hbd'* - count of H-bonds donor 

*'psa'* -  the surface sum over all polar atoms of a molecule 

*'rtb'* - number of free rotateble bonds

*'cx_most_apka'* - pKa

*'cx_most_bpka'* - pKb    
       
*'num_ro5_violations'* - number of free rotateble bonds (drop)
