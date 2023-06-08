# llm-legal-advice-demo
Large language models to give legal advices.


## Merging index files

Some files were split to avoid github file size limit.

Merge them before loading the db index.

```bash
cd chroma_db_store
cat chroma-embeddings.parquet.parta* > chroma-embeddings.parquet
cd index
cat index_f34e12d7-1d6b-43d4-a713-33cbba2382c6.bin.parta* > index_f34e12d7-1d6b-43d4-a713-33cbba2382c6.bin
```
