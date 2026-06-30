# PakNotes Colab

Use [paknotes_db_colab.ipynb](/D:/PakNotesDB/colab/paknotes_db_colab.ipynb) in Google Colab to work with the `english_mcqs.db` SQLite database.

The notebook supports two ways to load the database:

1. Mount Google Drive and open a DB file already stored there.
2. Upload `english_mcqs.db` directly from your computer into the Colab session.

Recommended source file from this repository:

- `D:\PakNotesDB\data\english_mcqs.db`

Once loaded, the notebook:

- connects to SQLite,
- lists tables,
- previews rows from `mcqs`,
- shows row counts for the main tables,
- and includes a custom query cell you can edit.
