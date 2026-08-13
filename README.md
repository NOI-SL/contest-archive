# NOI Sri Lanka — Contest Archive

Problem statements from the National Olympiad in Informatics Sri Lanka, published with
GitHub Pages: **<https://archive.noi.lk>**

Covers final rounds, selection/qualifier rounds and monthly contests, 2019–2026. Statements were
archived from the HackerRank contests they were originally hosted on; the original markdown and
LaTeX are preserved.

## How it is laid out

```
_problems/<year>/<category>/<contest>/NN-<problem-slug>.md   the statements (one file per problem)
_layouts/                                                    two small HTML layouts
assets/problems/                                             images used by statements
assets/css/style.css                                         all the styling
index.md                                                     builds itself from _problems
_data/stats.yml                                              contest count shown on the home page
```

`<category>` is one of `finals`, `qualifier` or `monthly`:

```
_problems/2022/finals/day-1/02-two-spindles.md   ->  /2022/finals/day-1/02-two-spindles/
_problems/2022/monthly/03-march/01-not-so-safe.md
_problems/2022/qualifier/01-the-brackets.md
```

The home page is generated from the files by Liquid — **there is no index to update by hand.**
Add a file in the right folder with the right front matter and it shows up.

## Adding a contest

Create one file per problem under `_problems/<year>/<category>/<contest>/` and copy this front
matter, changing the values:

```yaml
---
title: "Two Spindles"
year: 2022
category: finals              # finals | qualifier | monthly
round: "Final Round — Day 1"  # heading the problem is grouped under on the home page
sortkey: "3-finals-1-02"      # controls ordering within the year, see below
index: 2                      # position within its own contest
max_score: 100
difficulty: "Medium"
contest_name: "National Olympiad in Informatics Sri Lanka 2022 - Day 1"
contest_slug: "noi-2022-day-1"
contest_url: "https://www.hackerrank.com/contests/noi-2022-day-1"
problem_slug: "two-spindles"
problem_url: "https://www.hackerrank.com/contests/noi-2022-day-1/challenges/two-spindles"
---
```

Everything below the front matter is the statement in markdown. `layout: problem` is applied
automatically, so you don't need to write it.

`sortkey` decides the order the rounds and problems appear in under a year. It is just a string
that sorts correctly:

| Round type | Pattern | Example |
|---|---|---|
| Selection / qualifier | `1-qualifier-NN` | `1-qualifier-03` |
| Monthly | `2-monthly-MM-NN` | `2-monthly-03-01` (March, problem 1) |
| Finals | `3-finals-D-NN` | `3-finals-2-01` (Day 2, problem 1) |

### Maths

Wrap **all** maths in `$$…$$`, inline as well as display — `$$n \le 10^6$$`. Single-dollar
`$…$` is not safe here: kramdown treats the underscores and asterisks inside it as markdown
formatting and mangles the expression. Rendering is done by MathJax, loaded in
`_layouts/default.html`.

### Images

Put the file in `assets/problems/` and reference it through `relative_url` so it keeps working
regardless of where the site is hosted:

```markdown
![](  {{ "/assets/problems/my-figure.png" | relative_url }} )
```

## Running it locally

```bash
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000/>.

## Domain

The site is served from `archive.noi.lk`, set by the `CNAME` file at the repo root. DNS is a
Cloudflare `CNAME` record `archive` -> `noi-sl.github.io`, left **unproxied (grey cloud)** so that
GitHub can issue and renew the TLS certificate.

To go back to `noi-sl.github.io/contest-archive/`, delete `CNAME` and set
`baseurl: /contest-archive` in `_config.yml`. Every internal link goes through `relative_url`,
so nothing else needs to change.

## Machine-readable index

`metadata.json` lists every contest and problem with its HackerRank URL and file path.

## Licence

Site and tooling: MIT (see `LICENSE`). The problem statements remain the property of the National
Olympiad in Informatics Sri Lanka and their authors.
