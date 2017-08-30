http://issuetemplate.com/#/processmap/cosmos/cosmos-user-story

#### Template Notes
```
### Document Management - User Stories

**User stories** are short, simple descriptions of a feature told from the perspective of the person who desires the new capability, usually a user or customer of the system. They typically follow a simple template:

#### As a `<type of user>`, I want `<some goal>` so that `<some reason>`.
```

#### Issue Title Template
```
As {{field0}}, I want to {{field1}}, so that {{field2}}
```

#### Field 0
Name:`Type of User`
Help Text:
```
For what type of user will this story be? (ex. owner, coordinator, approver, reader, auditor)
```
Element: `blank`
Values: 
```
owner, coordinator, approver, reader, auditor, manager, corporate
```
#### Field 1
Name: `Goal` 
Help text:
```
What goal does the user {{field0}} wants to achieve?
```
Element: `textarea`
Element Type: `text`
Values: `ex. to achieve something great`

#### Field 2
Name: `Reason` 
Help text:
```
What reason(s) does the user {{field0}} have for using this feature?
```
Element: `textarea`
Element Type: `text`
Values: `ex. s/he can have a business value.`

#### Field 3
Name: `Priority` 
Help text:
```
How critical is this for the end-user on day-1?
```
Element: `select`
Element Type: `blank`
Values: `without this we're screwed, we can buy time without it, please keep it in our radar`

#### Field 4
Name: `MVP` 
Help text:
```
What is the simplest way this story can be implemented on day-1?
```
Element: `textarea`
Element Type: `text`
Values: `ex. a simple checkbox should do the trick.`

#### Field 5
Name: `Bonus` 
Help text:
```
How can this MVP be enhanced in future sprints?
```
Element: `textarea`
Element Type: `text`
Values: `ex. make it shake!`

#### Field 6
Name: `SME` 
Help text:
```
Who should we contact to get more information about this request? (ex. module developer, PM's name)
```
Element: `textarea`
Element Type: `text`
Values: `blank`

---
#### Template Body
```
### As {{field0}}, I want {{field1}}, so that {{field2}} 
---
Please describe further in the __Other Comments__ textarea with links, examples, images, etc.
---
#### Priority:
### __{{field3}}__
---
#### Acceptance Criteria:

__MVP:__ What is the simplest way this story can be implemented on day-1?
##### {{field4}}
---
__Bonus:__
How can this MVP be enhanced in future sprints?
##### {{field5}}
---
__SME:__ Who should we contact to get more information about this request? 
##### {{field6}}

```