# CRIStin

This Github repository contains material such as code and configuration for CRIStin.

## DSpace

### Installing the CRIStin metadata registry

The DSpace CRIStin metadata registry is available at https://github.com/joomlaarchive/cristin/blob/master/dspace/config/registries/cristin-types.xml.

To install:

- Copy the cristin-types.xml to your DSpace server,
- Locate the dspace command line tool (/path/to/dspace/bin/),
- Run the dspace command's metadata registry loader.

To run the dspace registry loader (where /path/to/dspace/bin is the path to the dspace command line tool):

```
/path/to/dspace/bin/dspace registry-loader -metadata /opt/dspace/config/registries/cristin-types.xml
```