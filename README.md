# salon-de-la-data
Visualisations pour les 10 ans du Salon de la Data à Nantes.

## Coding Guidelines

The code language for this repository is English in order to encourage
sharing.  In principle, variable names and code comments are in English.

Github workflows try to enforce some basic sanity.  For the python
code, the workflow enforces black formatting with 79 character line
limits and basic PEP-8 stuff via flake8.

Github is configured to require linear history, that tests succeed
before merging and to refuse pushes to main that are not associated
with a passing branch.  Merges require approval from anyone with
commit privileges.

Branches should begin with the name of the person who created it and
end with an issue number if there is an issue.  Ideally, there should
be an issue for all but trivial fixes.

Commit comments should have a declarative title of at most 50
characters, a blank space, then appropriate description of what the
commit does.  The last line should include issue tags.
