<div align="center">

# migration.log

<sub>a running log of systems moved from where they were to where they should be</sub>

</div>

<br>

```diff
- legacy database, unstructured, isolated
+ modern schema, normalized, integrated
```

I'm Danilo — a Computer Science student (UFAL) who keeps ending up on the
same kind of problem: **data that outgrew the system it's trapped in.**
Spreadsheets that became databases. Databases that became the wrong
database. Institutional knowledge scattered across formats nobody wants
to touch. I move it somewhere better, and I make sure nothing breaks on
the way there.

<br>

## `status --current`

<table>
<tr>
<td width="50%" valign="top">

**SIPROT / CNART @ NEES**
Legacy MySQL Server, Excel → PostgreSQL, full schema redesign, for a
federal cultural heritage system (IPHAN) integrated with **gov.br**.

`MySQL` `PostgreSQL` `Python` `Liquibase`

</td>
<td width="50%" valign="top">

**Library Repository @ UFAL**
University thesis/dissertation archive (Odoo-based) → **DSpace**,
the international open repository standard.

`Odoo` `DSpace` `Schema Mapping`
[`repo →`](https://github.com/NTI-UFAL-Arapiraca/dspace-migration)

</td>
</tr>
</table>

<br>

## `stack --primary`

<div align="center">

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

</div>

<br>

## `log --oneline`

```
a1b2c3d  migrate(cnart,siprot): MySQL Server, Excel -> PostgreSQL, schema redesign
e4f5g6h  migrate(library): Odoo -> DSpace, thesis/dissertation archive
i7j8k9l  analyze(rais): raw labor market spreadsheets -> automated pandas pipeline
m0n1o2p  init: Computer Science, Federal University of Alagoas
```

<br>

<div align="center">

<sub>
if the data works but nobody trusts it, it isn't done yet.
</sub>

</div>
