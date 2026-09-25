# FIT5202 | Melbourne parking & congestion

PySpark analysis of parking activity, parking violations, long-stay bays and traffic volume. The notebook covers typed ingestion, data-quality checks, DataFrame and SQL analysis, execution plans, and a query-optimisation comparison.

## Run
Install the packages in `requirements.txt`, with a Java installation compatible with your chosen Spark version. Set `A1_DATA_DIR` to your local dataset directory and open `parking-congestion-analysis.ipynb` in Jupyter.

Required files: `sensordata.csv`, `traffic_count.csv`, `area.json`, `street.json`. Obtain the course dataset through your authorised source. The local sensor CSV is approximately 9.20 GB and traffic CSV is 225 MB; neither is redistributed. The 121 MB notebook PDF and screenshot archive are also omitted.

This publication clears notebook outputs and local execution metadata. The underlying analysis has not been rerun for this portfolio release. No benchmark result is independently asserted here.
