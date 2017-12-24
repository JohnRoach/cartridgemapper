# Endeca Cartridge Mapper

[![Build Status](https://travis-ci.org/JohnRoach/cartridgemapper.svg?branch=master)](https://travis-ci.org/JohnRoach/cartridgemapper)

This cool tool scans a given Endeca Application an generates documentation regarding the cartridges in HTML or JSON form.

The documentation includes information such as:
- Name of cartridge
- ID of cartridge
- Description of cartridge
- Endeca rules that use cartridge
- Sites that use cartridge
- Pages that use said cartridge

Sample run:

```
cartridgemapper mapEndecaApp /full/path/to/endeca/App/lication
```