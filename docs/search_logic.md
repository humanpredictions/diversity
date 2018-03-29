## humanpredictions search logic

We use [genderize.io](https://genderize.io/) to guess gender via name, returning
anyone who genderize guesses is a woman.

Anyone with any of these [keywords](../spreadsheets/keywords.csv) on any
field of their publicly available profiles.

Anyone who is a member of any of these
[Groups/Organizations](../spreadsheets/groups_and_organizations.csv).

All terms are joined together by OR strings.

## Contributions
We are exposing the logic that we use in hopes to gain insights and advice from
smarter people like YOU. If you think we can do better in some aspect of our
diversity search logic:
* submit an issue or [contact us](mailto:diversity@humanpredictions.io)
* contribute to our list of keywords or Groups/Organizations through a pull
  request

