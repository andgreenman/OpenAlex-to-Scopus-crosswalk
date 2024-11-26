# OpenAlex-to-Scopus-crosswalk

### Metadata crosswalk for OpenAlex web records exports to Scopus records export format for use in bibliometric analysis tools.

The goal of this project was to take an OpenAlex export, which can be used to a limited extent in Biblioshiny but cannot be used in VOSviewer, and crosswalk it to Scopus' export format, which can. Corresponding columns are selected, column spacing is padded with empty columns matching Scopus format, and a variety of transformations are applied to the data. OpenAlex references are trimmed to the OpenAlex IDs, then the OpenAlex API is used to replace the list of referenced OpenAlex IDs with plain text references.
