---
availability: INSTALLABLE
description: Plugin to create a task for an user and assign projects, start date,
  due date.
diffuculty: BEGINNER
domain:
- Productivity
- Project Management
fidelity: TEMPLATE
installation_asset_uuid: 83e4acde-61c5-4f93-b617-b0b968b2945a
name: Create a Task
purple_chat_link: https://developer.moveworks.com/creator-studio/developer-tools/purple-chat?conversation=%7B%22startTimestamp%22%3A%2211%3A43+AM%22%2C%22messages%22%3A%5B%7B%22parts%22%3A%5B%7B%22richText%22%3A%22I+want+to+create+a+new+task+and+assign+it+to+a+user.%22%7D%5D%2C%22role%22%3A%22user%22%7D%2C%7B%22parts%22%3A%5B%7B%22richText%22%3A%22Okay%2C+I+can+help+with+that.+Let%27s+gather+some+details.%5Cn%5CnWho+should+I+assign+the+task+to%3F%22%7D%5D%2C%22role%22%3A%22assistant%22%7D%2C%7B%22parts%22%3A%5B%7B%22richText%22%3A%22John+Doe%22%7D%5D%2C%22role%22%3A%22user%22%7D%2C%7B%22parts%22%3A%5B%7B%22reasoningSteps%22%3A%5B%7B%22richText%22%3A%22Searching+for+user+%5C%22John+Doe%5C%22+in+the+system...%22%2C%22status%22%3A%22pending%22%7D%2C%7B%22richText%22%3A%22Found+2+possible+matches.%22%2C%22status%22%3A%22success%22%7D%5D%7D%2C%7B%22richText%22%3A%22I+found+a+couple+of+matches+for+%5C%22John+Doe.%5C%22%22%7D%2C%7B%22buttons%22%3A%5B%7B%22buttonText%22%3A%22John+Doe+%28john.doe%40example.com%29%22%2C%22style%22%3A%22outlined%22%7D%2C%7B%22buttonText%22%3A%22John+Doe+%28john.d%40example.com%29%22%2C%22style%22%3A%22outlined%22%7D%5D%7D%5D%2C%22role%22%3A%22assistant%22%7D%2C%7B%22parts%22%3A%5B%7B%22richText%22%3A%22John+Doe+%28john.doe%40example.com%29%22%7D%5D%2C%22role%22%3A%22user%22%7D%2C%7B%22parts%22%3A%5B%7B%22richText%22%3A%22Got+it.+Which+project+should+this+task+be+associated+with%3F%22%7D%5D%2C%22role%22%3A%22assistant%22%7D%2C%7B%22parts%22%3A%5B%7B%22richText%22%3A%22Project+Evergreen%22%7D%5D%2C%22role%22%3A%22user%22%7D%2C%7B%22parts%22%3A%5B%7B%22richText%22%3A%22Okay.+What+should+the+task+name+be%3F%22%7D%5D%2C%22role%22%3A%22assistant%22%7D%2C%7B%22parts%22%3A%5B%7B%22richText%22%3A%22Design+new+homepage%22%7D%5D%2C%22role%22%3A%22user%22%7D%2C%7B%22parts%22%3A%5B%7B%22richText%22%3A%22And+when+should+this+task+be+due%3F%22%7D%5D%2C%22role%22%3A%22assistant%22%7D%2C%7B%22parts%22%3A%5B%7B%22richText%22%3A%22Next+Friday%22%7D%5D%2C%22role%22%3A%22user%22%7D%2C%7B%22parts%22%3A%5B%7B%22richText%22%3A%22%3Cp%3EOkay%2C+I+have+the+following+details%3A%3C%2Fp%3E%5Cn%3Cp%3E%3Cstrong%3EAssignee%3C%2Fstrong%3E%3AJohn+Doe+%28john.doe%40example.com%29%26nbsp%3B%3C%2Fp%3E%5Cn%3Cp%3E%3Cstrong%3EProject%3C%2Fstrong%3E%3A+Project+Evergreen%26nbsp%3B%3C%2Fp%3E%5Cn%3Cp%3E%3Cstrong%3ETask+Name%3C%2Fstrong%3E%3A+Design+new+homepage%26nbsp%3B%3C%2Fp%3E%5Cn%3Cp%3E%3Cstrong%3EDue+Date%3C%2Fstrong%3E%3ANext+Friday%26nbsp%3B%3C%2Fp%3E%5Cn%3Cp%3ECreate+the+task%3F%3C%2Fp%3E%22%7D%2C%7B%22buttons%22%3A%5B%7B%22buttonText%22%3A%22Create+Task%22%2C%22style%22%3A%22filled%22%7D%2C%7B%22buttonText%22%3A%22Edit+Details%22%2C%22style%22%3A%22outlined%22%7D%2C%7B%22buttonText%22%3A%22Cancel%22%2C%22style%22%3A%22outlined%22%7D%5D%7D%5D%2C%22role%22%3A%22assistant%22%7D%2C%7B%22parts%22%3A%5B%7B%22richText%22%3A%22Create+Task%22%7D%5D%2C%22role%22%3A%22user%22%7D%2C%7B%22parts%22%3A%5B%7B%22richText%22%3A%22OK.+I%27ve+created+the+task.%22%7D%2C%7B%22citations%22%3A%5B%7B%22citationTitle%22%3A%22Design+new+homepage%22%2C%22connectorName%22%3A%22asana%22%7D%5D%7D%5D%2C%22role%22%3A%22assistant%22%7D%5D%7D
solution_tags:
- Productivity
- Project Management
systems:
- asana
time_in_minutes: 15
---

# Introduction

The **Create Task in Asana** plugin enables your users to add tasks to an Asana project directly through the Moveworks AI Assistant. Users can specify task details such as name, description, due date, and assignee, ensuring seamless task management without leaving their chat interface.

This guide will help you install this plugin within minutes in Agent Studio. Let’s get started!

# Prerequisites

- Access to Agent Studio
- [Asana Connector](https://developer.moveworks.com/creator-studio/resources/connector?id=asana) set up in Creator Studio
- [Get a List of my Projects](https://developer.moveworks.com/creator-studio/resources/plugin?id=asana-list-projects) Plugin

# What are we building?

## Agent Design

This [purple chat](https://developer.moveworks.com/creator-studio/developer-tools/purple-chat?conversation=%7B%22startTimestamp%22%3A%2211%3A43+AM%22%2C%22messages%22%3A%5B%7B%22parts%22%3A%5B%7B%22richText%22%3A%22I+want+to+create+a+new+task+and+assign+it+to+a+user.%22%7D%5D%2C%22role%22%3A%22user%22%7D%2C%7B%22parts%22%3A%5B%7B%22richText%22%3A%22Okay%2C+I+can+help+with+that.+Let%27s+gather+some+details.%5Cn%5CnWho+should+I+assign+the+task+to%3F%22%7D%5D%2C%22role%22%3A%22assistant%22%7D%2C%7B%22parts%22%3A%5B%7B%22richText%22%3A%22John+Doe%22%7D%5D%2C%22role%22%3A%22user%22%7D%2C%7B%22parts%22%3A%5B%7B%22reasoningSteps%22%3A%5B%7B%22richText%22%3A%22Searching+for+user+%5C%22John+Doe%5C%22+in+the+system...%22%2C%22status%22%3A%22pending%22%7D%2C%7B%22richText%22%3A%22Found+2+possible+matches.%22%2C%22status%22%3A%22success%22%7D%5D%7D%2C%7B%22richText%22%3A%22I+found+a+couple+of+matches+for+%5C%22John+Doe.%5C%22%22%7D%2C%7B%22buttons%22%3A%5B%7B%22buttonText%22%3A%22John+Doe+%28john.doe%40example.com%29%22%2C%22style%22%3A%22outlined%22%7D%2C%7B%22buttonText%22%3A%22John+Doe+%28john.d%40example.com%29%22%2C%22style%22%3A%22outlined%22%7D%5D%7D%5D%2C%22role%22%3A%22assistant%22%7D%2C%7B%22parts%22%3A%5B%7B%22richText%22%3A%22John+Doe+%28john.doe%40example.com%29%22%7D%5D%2C%22role%22%3A%22user%22%7D%2C%7B%22parts%22%3A%5B%7B%22richText%22%3A%22Got+it.+Which+project+should+this+task+be+associated+with%3F%22%7D%5D%2C%22role%22%3A%22assistant%22%7D%2C%7B%22parts%22%3A%5B%7B%22richText%22%3A%22Project+Evergreen%22%7D%5D%2C%22role%22%3A%22user%22%7D%2C%7B%22parts%22%3A%5B%7B%22richText%22%3A%22Okay.+What+should+the+task+name+be%3F%22%7D%5D%2C%22role%22%3A%22assistant%22%7D%2C%7B%22parts%22%3A%5B%7B%22richText%22%3A%22Design+new+homepage%22%7D%5D%2C%22role%22%3A%22user%22%7D%2C%7B%22parts%22%3A%5B%7B%22richText%22%3A%22And+when+should+this+task+be+due%3F%22%7D%5D%2C%22role%22%3A%22assistant%22%7D%2C%7B%22parts%22%3A%5B%7B%22richText%22%3A%22Next+Friday%22%7D%5D%2C%22role%22%3A%22user%22%7D%2C%7B%22parts%22%3A%5B%7B%22richText%22%3A%22%3Cp%3EOkay%2C+I+have+the+following+details%3A%3C%2Fp%3E%5Cn%3Cp%3E%3Cstrong%3EAssignee%3C%2Fstrong%3E%3AJohn+Doe+%28john.doe%40example.com%29%26nbsp%3B%3C%2Fp%3E%5Cn%3Cp%3E%3Cstrong%3EProject%3C%2Fstrong%3E%3A+Project+Evergreen%26nbsp%3B%3C%2Fp%3E%5Cn%3Cp%3E%3Cstrong%3ETask+Name%3C%2Fstrong%3E%3A+Design+new+homepage%26nbsp%3B%3C%2Fp%3E%5Cn%3Cp%3E%3Cstrong%3EDue+Date%3C%2Fstrong%3E%3ANext+Friday%26nbsp%3B%3C%2Fp%3E%5Cn%3Cp%3ECreate+the+task%3F%3C%2Fp%3E%22%7D%2C%7B%22buttons%22%3A%5B%7B%22buttonText%22%3A%22Create+Task%22%2C%22style%22%3A%22filled%22%7D%2C%7B%22buttonText%22%3A%22Edit+Details%22%2C%22style%22%3A%22outlined%22%7D%2C%7B%22buttonText%22%3A%22Cancel%22%2C%22style%22%3A%22outlined%22%7D%5D%7D%5D%2C%22role%22%3A%22assistant%22%7D%2C%7B%22parts%22%3A%5B%7B%22richText%22%3A%22Create+Task%22%7D%5D%2C%22role%22%3A%22user%22%7D%2C%7B%22parts%22%3A%5B%7B%22richText%22%3A%22OK.+I%27ve+created+the+task.%22%7D%2C%7B%22citations%22%3A%5B%7B%22citationTitle%22%3A%22Design+new+homepage%22%2C%22connectorName%22%3A%22asana%22%7D%5D%7D%5D%2C%22role%22%3A%22assistant%22%7D%5D%7D) shows the experience we are going to build.

# Installation Steps

While you can create a connector during plugin installation, we do recommend that you create a connector in Agent Studio before installing this plugin to streamline the process. Please follow our **Asana Connector Guide** to do so. Once you have done this, simply follow our plugin installation documentation to get your plugin installed in minutes.

Required Scopes:

- `tasks:write` – To create tasks in Asana

After you have configured the connector, please refer to our installation documentation for more information on how to install a plugin.

# Appendix

The [Create a Task](https://developers.asana.com/reference/createtask) API allows you to add a new task to a specified Asana project.

```bash
curl --request POST \
     --url https://app.asana.com/api/1.0/tasks \
     --header 'accept: application/json' \
     --header 'authorization: Bearer {{personal_access_token}}' \
     --header 'content-type: application/json' \
     --data '{
       "data": {
         "name": "{{task_name}}",
         "notes": "{{task_description}}",
         "due_on": "{{due_date}}",
         "start_on": "{{start_on}}",
         "assignee": "{{assignee_gid}}",
         "projects": ["{{project_gid}}"]
       }
     }'
```

**Required Body Parameters:**

- **`name`** (string) – Name of the task.
- **`projects`** (array) – The project(s) where the task should be created.

**Optional Body Parameters:**

- **`notes`** (string) – Task description.
- **`due_on`**(string) – Task due date in `YYYY-MM-DD` format.
- **`start_on`** (string) – Task start date in `YYYY-MM-DD` format.
- **`assignee`** (string) – GID of the user assigned to the task.
- **`followers`** (array) – List of user GIDs to be added as followers.