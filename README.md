# jenkimon

Either download and open `/path/to/index.html?server=http://myjenkins`, or visit
<http://esendex.github.io/jenkimon/?server=http://myjenkins> where the value of
`?server=` is set to the url (including protocol) of the root of your jenkins
install.

## Options

Name           | Description
---------------|------------------------------------------------------------------------
`server`       | Path to jenkins including protocol
`theme`        | Choose a different theme from: neon.
`filters`      | Comma separated list of words to filter displayed jobs by
`scope`        | The method of filtering, see options below
`showInactive` | Set to anything to show inactive jobs
`bonusRound`   | Choose something to display when "green"

### Scopes

Name         | Description
-------------|------------------------------------------------------------------------
`contains`   | _Default_ Matches if job name contains a filter
`startsWith` | Matches if job name starts with a filter
`exclude`    | The inverse of `contains`; excludes jobs where name contains a filter

### Bonus Rounds

- green
- cat
- porkour
