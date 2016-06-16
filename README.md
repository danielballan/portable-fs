# Portable Metadatastore

an implementation of the metadatastore interface in front of alternative
backends that do not require a Mongo interface

* JSON headers and events
* JSON headers and HDF5 events
* JSON headers and sqlite events

See `example_migration.py` above for an example of moving documents from
a standard MongoDB-backed metadatastore to a lighter JSON-backed metadatastore.
