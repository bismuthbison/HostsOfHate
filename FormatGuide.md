# Format/Style Guide For Hosts of Hate

## File Type
All file types containing infomation are in markdown `.md` format with the exception of any scripts or the host file itself that needs to be a text. 

## File Organization
- Each organization/site and person has their own file.
    - People are under the people folder
    - Sites are under organization 
- Resources are databases, journalist and publications that are sourced for this. 

## YAML Front Matter
The start of each file should contain YAML front matter, this is so scripts can process it to build host files and block/monitoring list. The list of front matter properties will keep expanding as time goes on. 

### Alias (array)
Some Hosts of Hate will have aliases, this should be an array 
```YAML
alias:
- Agent Orange
- Lost Slug
```
### FascTags (array)

These are specific tags of movements they belong to and ideologies they may express. These are the current FascTags. 
#### Transphobia
Regularly tragets trans people.
#### Homophobia
#### White Supremacist
#### Targets Journalist
Do they call for violent action against journalist.
### Brownshirt
Since some sites don't let you say the name that rhyms with Yahtzee. 
### Death Lible
As not to completly co-op the terrible practice of blood lible, death lible is a group tries to manufacture consent of violence towards another group.