# Boolean Search Cheat Sheet for Recruiters

A short guide to finding the right candidates on job portals and professional networks with Boolean search, with ready-to-adapt examples for common roles in IT, engineering, enterprise applications, healthcare and sales.

Search tools behave differently and change over time, so test each string on the platform you use and adjust it.

## The basics

| Operator | What it does | Example |
|---|---|---|
| `AND` | Both terms must appear | `Java AND "Spring Boot"` |
| `OR` | Either term can appear | `"Data Engineer" OR "ETL Developer"` |
| `NOT` | Excludes a term | `Java NOT intern` |
| `" "` | Matches an exact phrase | `"business analyst"` |
| `( )` | Groups terms, so the logic is read in the order you intend | `(Java OR Kotlin) AND Hyderabad` |

Write the operators in capital letters.

## Examples by role

**C++ developer on Linux, Hyderabad**

```
("C++" OR "C plus plus") AND (Linux OR Unix) AND (Hyderabad OR Secunderabad) NOT (intern OR trainee)
```

**Java full-stack developer**

```
(Java OR J2EE) AND ("Spring Boot" OR Spring) AND (React OR Angular) AND (Hyderabad OR Secunderabad)
```

**Data engineer**

```
("Data Engineer" OR "ETL Developer") AND (Python OR SQL) AND (Spark OR Airflow OR "Azure Data Factory")
```

**Oracle Fusion Finance consultant**

```
("Oracle Fusion" OR "Oracle Cloud") AND (Finance OR "General Ledger" OR Payables OR Receivables)
```

**PCB design engineer**

```
("PCB design" OR "PCB layout") AND (Altium OR OrCAD OR Allegro)
```

**Healthcare business analyst**

```
("Business Analyst" OR "Functional Consultant") AND (Healthcare OR "Health Insurance" OR Clinical)
```

**FMCG sales**

```
(FMCG OR "consumer goods") AND (sales OR "business development") AND ("distributor management" OR "channel sales")
```

## Tips

1. **Start with the skills that matter most**, not the whole job description. Add one condition at a time and check how many results you get.
2. **Add synonyms for every skill and title.** People write the same role in different ways, such as "Software Engineer", "Developer" and "SDE".
3. **Include location variants**, such as Hyderabad and Secunderabad.
4. **Use `NOT` sparingly.** It can hide good profiles. Exclude only terms that clearly make a profile wrong, such as "intern" for a senior role.
5. **Keep strings readable.** Use brackets and put each group on its own line while you build it, then join it up.
6. **Save the strings that work** in a document so you can reuse them.
7. **Respect candidate privacy.** Use candidate details only for hiring, and don't share them outside the process.
