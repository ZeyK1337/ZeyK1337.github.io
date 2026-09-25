# FIT5196 | Commerce data integration & quality

**Group029, members 1-2 integrated working version.** This is a collaborative coursework artefact, not a claim of sole authorship or a finished six-table pipeline. The supplied handoff documents describe each member's work. `deliveries` and `product_reviews` still require integration.

The pipeline parses JSON/XML, standardises customers/products/orders/order items, checks cross-source conflicts, validates keys and monetary totals, and produces exploratory figures. The original handoff records 5,000 canonical orders, 15,706 order items and 22 passing member-2 validation checks. These are recorded results, not a new execution for publication.

## Run
Install `requirements.txt`. Place authorised `Group029_commerce.json` and `Group029_operations.xml` in `raw_package/raw_input/`, then run from this folder:

```sh
python src/group029_member2.py . --make-figures
python -m unittest discover -s tests -v
```

The source records and row-level exported CSVs are not redistributed. Notebook outputs were cleared for this public copy. Rebuild outputs before running the EDA notebook. Original collaboration notes are in `docs/`.
