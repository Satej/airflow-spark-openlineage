# airflow-spark-openlineage

```bash
git clone https://github.com/OpenLineage/OpenLineage
cd integration/spark
mkdir -p docker/notebooks/gcs
# Before next step, copy the files docker-compose.yml to this folder along
# with entrypoint.sh and wait-for-it.sh to docker directory.
docker-compose up
# In jupyter, go into the notebooks directory and upload the file Untitled.ipynb,
# replace with your own credential and config from gcs.
# Run the notebook and then check the marquez interface to see the jobs.
# Reference: https://openlineage.io/docs/guides/spark/
```