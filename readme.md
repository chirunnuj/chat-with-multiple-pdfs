### Important Note

Due to recent changes in Sentence-Transformers, they cause the follow error:

```
    TypeError: INSTRUCTOR._load_sbert_model() got an unpected keyword argument 'token'
```

Try lower version of Sentence-Transformers

```
    pip uninstall sentence-transformers
    pip install sentence-transformers=2.2.2

```
