# Walmart Bulk Upload Templates

Portfolio documentation for organizing Walmart bulk item setup and catalog updates.

## Included Files
- [Bulk Upload QA Checklist](bulk_upload_qa_checklist.md)
- [Demo Bulk Catalog](sample_bulk_catalog.csv)

## Recommended Working Columns

| Source Field | Marketplace Field | Required? | QA Status |
|---|---|---|---|
| SKU | SKU | Yes | Review |
| Product Name | Product Name | Yes | Review |
| Brand | Brand | Category dependent | Review |
| Color | Color | Category dependent | Review |
| Size | Size | Category dependent | Review |

## Bulk Upload Process
1. Preserve a clean source-of-truth file.
2. Map source columns to marketplace attributes.
3. Validate required fields and allowed values.
4. Review identifiers and variants.
5. Upload a small test batch.
6. Record processing errors.
7. Correct the source file.
8. Re-upload and perform live QA.

This repository uses generic examples and does not redistribute Walmart templates or confidential client files.

**Upwork:** https://www.upwork.com/freelancers/~0115a312ed543a19a1
