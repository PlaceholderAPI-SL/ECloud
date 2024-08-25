# ECloud - Database
Gives the access to developers to deliver their extension in real time to the servers

# How to add the Expansion?
Please, open a pull request adding to `data.yml` your `Expansion Name` and `Reposiotory ID`

```yml
# Example Expansion
- id: "Expansion Example"
  repoid: 1
```

## How can i get the RepoId?
use this code inside the console while in a github page to get it
`$("meta[name=octolytics-dimension-repository_id]").getAttribute('content')`
