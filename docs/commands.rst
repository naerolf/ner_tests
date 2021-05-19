Commands
========

The Makefile contains the central entry points for common tasks related to this project.

Syncing data to S3
^^^^^^^^^^^^^^^^^^

* `make sync_data_to_s3` will use `aws s3 sync` to recursively sync files in `data/` up to `s3://ds-stuff-74831cea-75a2-4dcf-a094-e8b61042a009/data/`.
* `make sync_data_from_s3` will use `aws s3 sync` to recursively sync files from `s3://ds-stuff-74831cea-75a2-4dcf-a094-e8b61042a009/data/` to `data/`.
