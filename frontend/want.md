- user rating in a group, user max rating in a group
- given a pair (user, group), return list of all contests user has taken part in (wrt group) along with metadata (contest id, rating after this contest)
- initial rating of a user in a group (when the user joins a group, he enters an initial rating)[by default: 1500] 
- list of all members in a group
- to "contest object", add "contest name", "contest data and time"
- for every user, store the number of groups he is a part of
- conversely, for every group, store the number of users
- for every group, store the list of moderators and number of moderators
- a view of the form (contest, group)
- user participation in a certain contest wrt a certain group: 
[
    - internal_contest_id
    - rank in contest wrt group
    - final group rating after this contest
]
- within a contest object:
[
    - internal contest id
    - cf contest id
    - cf contest name
    - contest time
]
- create a report object:
[
    - report id
    - group id
    - the user the report is against
    - string that contains the actual report
]