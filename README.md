compare_db.json writes closest aas from rmids_full/pa-data-separate-chainupdate to db.json
get_gps reads db.json and writes to pa-data-gauge
clean_genomes reads pa-data-gauge and writes to pa-data-genome-full / pa-data-genome-exc.json
aa_counts reads pa-data-genome-full / pa-data-genome-exc and writes to pa-data-common.json
gp_aas reads pa-data-common and writes to pa-data-close.json / pa-data-dclosest.json / pa-data-gp-aas.json
OLD: assign-closest reads pa-data-common and writes to pa-data-final.json
properties reads pa-data-dclosest and writes to pa-data-properties.json
filters reads pa-data-properties and writes to pa-data-filters.json
gp_all_aas reads pa-data-filters and writes to pa-data-all-pas


