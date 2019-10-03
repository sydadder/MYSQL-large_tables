# large_tables
The size of tables that I have worked with


 SELECT       table_schema as `Database`,       table_name AS `Table`,       round(((data_length + index_length) / 1024 / 1024), 2) `Size in MB`  FROM information_schema.TABLES  ORDER BY (data_length + index_length) DESC;
+---------------------------+----------------------------------------------------+------------+
| Database                  | Table                                              | Size in MB |
+---------------------------+----------------------------------------------------+------------+
| flixcar                   | asset_feature                                      |   96079.66 |
| flixcar                   | asset                                              |   91561.72 |
| flixcar                   | asset_language                                     |   82426.94 |
| flixcar_import            | feed_review                                        |   62911.75 |
| flixcar                   | asset_specification                                |   46493.89 |
| flixcar                   | product_asset                                      |   40684.61 |
| flixcar_import            | hp_specification                                   |   40182.94 |
| flixcar                   | file                                               |   39109.34 |
| flixcar                   | product_accessory_new                              |   31381.59 |
| flixcar_import            | feed_queue_product                                 |   28176.69 |
| flixcar                   | asset_feature_file                                 |   25596.78 |
| distributor_sio           | distributor_feed_backup                            |   20690.66 |
| distributor_sio           | distributor_feed                                   |   20686.75 |
| flixcar_import            | feed_queue                                         |   18546.00 |
| distributor               | distributor_feed                                   |   13531.55 |
| flixcar_import            | default_specification                              |   13360.98 |
| flixcar_import            | default_missing_ean_mpn                            |   10508.00 |
| distributor_sio           | distributor_match                                  |    9497.72 |
| flixcar                   | product_asset_mobile                               |    9366.78 |
| flixcar                   | product_accessory                                  |    8455.00 |
| flixcar                   | asset_rich                                         |    6199.03 |
| flixcar_import            | feed_queue_product_version                         |    6119.27 |
| flixcar                   | product_asset_extrainfo                            |    5241.00 |
| flixcar                   | asset_image                                        |    4296.34 |
| flixfacts                 | tag_name                                           |    3524.81 |
| flixfacts                 | prod_cont_text                                     |    3377.55 |
| distributor               | distributor_feed_manual                            |    3018.81 |
| flixcar_import            | cron_log                                           |    2596.52 |
| bespoke                   | cloud_audit                                        |    2584.97 |
| flixfacts                 | click_tabs                                         |    2578.89 |
| flixcar                   | file_image                                         |    2457.80 |
| flixcar                   | product_title                                      |    2216.23 |
| flixcar                   | product_category                                   |    1900.73 |
| flixfacts                 | click_tabs_tmp                                     |    1588.95 |
| bespoke                   | cloud_audit_old                                    |    1503.00 |
| flixcar                   | product_indexing_data                              |    1321.02 |
| distributor               | distributor_feed_mpn                               |    1287.72 |
| flixcar                   | _ile__mage                                         |    1122.84 |
| flixfacts                 | prod_cont_image                                    |    1112.59 |
| flixcar_import            | feed_queue_product_asset                           |    1094.44 |
| distributor               | distributor_feed_upc                               |    1079.66 |
| flixfacts                 | click                                              |    1025.98 |
