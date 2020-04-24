# data!
| | Method |species| N datasets|gene list|spot table| cell x gene | notes|
| ----: | ---- | ---- | ---- | ---- | ---- | --- | --- |
| 1 |DARTFISH| *M. musculus* and *H. sapiens*| | [DARTFISH_genes](https://github.com/spacetx-spacejam/data/blob/master/gene_lists/DARTFISH_genes.csv)|[SpotTable Human 1 (frontal cortex)](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/DARTFISH/DARTFISH_DecodedSpots_Hs_FCtx_20180122.csv) [SpotTable Human 2 (occipital cortex)](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/DARTFISH/DARTFISH_DecodedSpots_Hs_OCtx_20180122.csv),  [SpotTable Mouse 1](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/DARTFISH/DARTFISH_DecodedSpots_Mm_20190513.csv)|[CellxGene Human (frontal cortex) 1](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/DARTFISH/DARTFISH_CellxGene_Hs_FCtx_20180122_T.csv),  [CellxGene Human 2 (occipital cortex)](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/DARTFISH/DARTFISH_CellxGene_Hs_OCtx_20180122_T.csv) [CellxGene Mouse 1](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/DARTFISH/DARTFISH_CellxGene_Mm_20190513_T.csv) | *xy in mouse should be multiplied by 0.144 to get microns*
| 2 |MERFISH (Zhuang: MOp) | *M. musculus* | | [MERFISH_genes](https://github.com/spacetx-spacejam/data/blob/master/gene_lists/MERFISH_genes.csv)|  | [file with S3 locations (Mouse, primary motor cortex)](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/MERFISH_zhuang_lab_MOp/file_list.csv) | 
| 3 |osmFISH| *M. musculus*| | [osmFISH_inhibitory_genes (mouse VISp)](https://github.com/spacetx-spacejam/data/blob/master/gene_lists/osmFISH_inhibitory_genes.csv), [osmFISH_excitatory_genes (mouse VISp)](https://github.com/spacetx-spacejam/data/blob/master/gene_lists/osmFISH_excitatory_genes.csv)|[New and Improved Data: excitatory](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/osmfish/osmFISH_excitatory_neurons_dataset.csv) [New and Improved Data: inhibitory](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/osmfish/osmFISH_inhibitory_neurons_dataset.csv)|*needs segmentation!*|[DAPI_excitatory_roi1_0-125_126-219](https://www.dropbox.com/s/0jpy2vnkjx9ppuj/DAPI_Excitatory_roi1_0-125_roi_126-219.zip?dl=0),[PolyT_excitatory_roi1_0-125_126-219](https://www.dropbox.com/s/ru0n11y2cfa88xu/PolyT_Excitatory_roi1_0-125_roi_126-219.zip?dl=0)
| 4 |BARISTASeq| *M. musculus*| | [BARISTASeq_genes](https://github.com/spacetx-spacejam/data/blob/master/gene_lists/BARISTASEQ_genes.csv)|[SpotTable Mouse VISp](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/BARISTASEQ/all_spots.csv)|[CellxGene Mouse VISp](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/BARISTASEQ/cell_by_gene.csv)
| 5 |ISS| *M. musculus* and *H. sapiens*| | [ISS_genes](https://github.com/spacetx-spacejam/data/blob/master/gene_lists/ISS_genes.csv)|[SpotTable Human 1 MTG(FOVs 540)](https://drive.google.com/file/d/17BaHMKY8k96wr8IPmrbN1McfX3_8PIZx/view) [SpotTable Mouse 1 VISp (FOVs 704)](https://drive.google.com/file/d/1OSGKWvO2E8Foq74_9h9vhnlbZ8CQtuDT/view) [SpotTable Human MTG 2 (FOVs 460)](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/ISS/ISS_1_spot_table.csv) [SpotTable Mouse VISp 2 (FOVs 140)](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/ISS/ISS_2_spot_table.csv) [SpotTable Mouse VISp 3 (FOVs 143)](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/ISS/ISS_3_spot_table.csv) [SpotTable Human MTG 3 (FOVs 378)](https://drive.google.com/open?id=15xHiftBM-esR5qijaNEMzD_QlzFTARP3) [SpotTable Human MTG 4 (FOVs 621)](https://drive.google.com/open?id=1iZwNZ7HRi8FguLhRbiZg61r43d7pPkvt)|[cellxgene Human MTG 1 (FOVs 540)](https://drive.google.com/open?id=1VjGa0QGHFRMRLQRAP1PGCkMjEVFVB_g5) [cellxgene Mouse VISp 1 (FOVs 704)](https://drive.google.com/open?id=1-o5Z4q1MMMa05Z6YZvgHEb6vNbRMBh8F) [cellxgene Human MTG 2 (FOVs 460)](https://drive.google.com/open?id=1uPo87acN9zsnQ3ezRnwfbq7m3B1wxcO0) [cellxgene Mouse VISp 2 (FOVs 140)](https://drive.google.com/open?id=1v5pwa1dgQk8x5W-ryXAyi9WbKNpFHGdG) [cellxgene Mouse VISp 3 (FOVs 143)](https://drive.google.com/open?id=1IYj3Nx5swsZwBy8rUouBsirV4unlSEzn) [cellxgene Human MTG 3 (FOVs 378)](https://drive.google.com/open?id=1l1fLPA1daH_63jBnFoH0h2EbWsWID1IT) [cellxgene  Human MTG 4 (FOVs 621)](https://drive.google.com/open?id=1NM_e2UpdBYXQ5ZlYFrGO9bY3NeV_H9bk) [Viktors genexcell](https://docs.google.com/spreadsheets/d/1Y_TapftVtEOo5JMtndVqct1lTw0hQOau35aPtdSjsTE/edit?usp=sharing). *|[DAPI Human 1 (FOVs 540)](https://drive.google.com/open?id=1tSpLXelKKVdU9zgN1neED6sVmz7Fc2fy) [DAPI Mouse 1 (FOVs 704)](https://drive.google.com/open?id=1ugNjkV5nDKcbh1T_SfiHtjnVEBiEhIMD) [DAPI Human 2 (FOVs 460)](https://drive.google.com/open?id=1kAULmZOgPIMLnRd65nyhlePk6odfqYg_) [DAPI Mouse 2 (FOVs 140)](https://drive.google.com/open?id=1KqPotQuFq7LAxLUam9UHe9FWZqn4grOk) [DAPI Mouse 3 (FOVs 143)](https://drive.google.com/open?id=1D71kiqhuqSgVbvr33dC_9lMPOKdDuQiI) [DAPI Human 3 (FOVs 378)](https://drive.google.com/open?id=1KsfrceNq9XagF0lpaF_g-dIuvZWsyHKd) [DAPI Human 4 (FOVs 621)](https://drive.google.com/open?id=1ydnHC8ZwEHrab3Uqhu1GVpEG0DAknXpd)
| 6 |ExSeq| *M. musculus*| | [ExSeq](https://github.com/spacetx-spacejam/data/blob/master/gene_lists/exseq_genes.csv)|[spot table](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/ExSeq/spottable_exseq.csv)|[CellxGene Table mouse](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/ExSeq/cellxgene.csv)||*...working on it...*
| 7 |SeqFISH| *M. musculus*| | [SeqFISH](https://github.com/spacetx-spacejam/data/blob/master/gene_lists/seqfish_genes.csv)|||*...working on it...*
| 8 |MERFISH (Allen: VISp, same panel as Zhuang lab above) | *M. musculus*| | [MERFISH_genes](https://github.com/spacetx-spacejam/data/blob/master/gene_lists/MERFISH_genes.csv)|[SpotTable Mouse VISp *with anatomy*](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/MERFISH_Allen_VISp/Allen_MERFISH_spots_with_anatomy.csv)|[CellxGene Mouse VISp](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/MERFISH_Allen_VISp/fixed_1001844875.csv)
|9|Allen smFISH VISp, (spacejam1)|*M. musculus*||[smfish_genes](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/smFISH_Allen/gene_list.csv)|[SpotTable Mouse VISp](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/smFISH_Allen/smFISH_MCT_CZI_Panel_0_spot_table.csv)||[nucleus segmentation (geojson)](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/smFISH_Allen/SongLinROIS_deduplicated.json)
|10|10x-Visium/ST| *M. musculus*|n/a|n/a|[observation x gene table 1](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/spatial-transcriptomics-alma/Allen-1-count-matrix.tsv.gz), [observation x gene table 2](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/spatial-transcriptomics-alma/Allen-2-count-matrix.tsv.gz), [observation x gene table 3](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/spatial-transcriptomics-alma/Allen-3-count-matrix.tsv.gz), [observation x gene table 4](https://s3.amazonaws.com/starfish.data.spacetx/spacejam2/spatial-transcriptomics-alma/Allen-4-count-matrix.tsv.gz)||*each file is a gzipped tsv* [Example analysis](https://github.com/almaan/spacetx)
|11|Slide-seq||||||*have lots of data, need help wrangling!*

# old data!
[**THIS SPREADSHEET**](https://docs.google.com/spreadsheets/d/1CN7kn8ELg9dhVPDkeb7JB02NYYTNUEqfaKkO40yWDzM/edit?usp=sharing) contains links to all the data and many of the analyses from the first spacejam, including the **RNA-seq reference data and consensus clusters**.  Several of these files are shared in the "spacetx" slack workspace.  Please ask [Jeremy](mailto:jeremym@alleninstitute.org) to invite you if needed, or if you have any questions about data access for things in this table.

# results!
## Please post your results [**HERE**](https://docs.google.com/spreadsheets/d/1Y_TapftVtEOo5JMtndVqct1lTw0hQOau35aPtdSjsTE/edit?usp=sharing)!
Add a row to the relevant sheet corresponding either to the data-set or meta-analysis that you have done or add additional sheets as needed.  Make sure the link to your result is here as well as a separate link (if needed) to some details about what your result actually means so others can use your results or compare their results against yours.
