---
banner: Attachments/Banner.png
banner-fade: 100
banner-radius: 50
cssclasses: homepage
---
<div class="home-buttons">
  <a class="internal-link" data-href="Projects/Project Hub" href="Projects/Project Hub">📁 Projects</a>
  <a class="internal-link" data-href="Education/Learning Hub" href="Education/Learning Hub">📚 Education</a>
  <a class="internal-link" data-href="Finance/Finance Dashboard" href="Finance/Finance Dashboard">📈 Finance</a>
  <a class="internal-link" data-href="Personal/Personal Hub" href="Personal/Personal Hub">🧠 Personal</a>
  <a class="internal-link" data-href="Other/Other" href="Other/Other">📦 Other</a>
</div>

<br>

```contributionGraph
title: ""
graphType: default
dateRangeValue: 365
dateRangeType: LATEST_DAYS
startOfWeek: "1"
showCellRuleIndicators: true
titleStyle:
  textAlign: center
  fontSize: 15px
  fontWeight: normal
dataSource:
  type: PAGE
  value: ""
  dateField:
    type: FILE_MTIME
fillTheScreen: false
enableMainContainerShadow: false
cellStyle:
  minWidth: 16px
  minHeight: 16px
cellStyleRules:
  - id: Wine_a
    color: "#d8b0b3"
    min: 1
    max: 2
  - id: Wine_b
    color: "#c78089"
    min: 2
    max: 3
  - id: Wine_c
    color: "#ac4c61"
    min: 3
    max: 5
  - id: Wine_d
    color: "#830738"
    min: 5
    max: 9999

```

> [!multi-column]
>
>> [!recent] Recent Notes
>> ```dataview
>> LIST
>> FROM ""
>> SORT file.mtime DESC
>> LIMIT 6
>> ```
>
>> [!projects] Active Projects
>> ```dataview
>> TABLE progress + "%" AS Progress
>> FROM "Projects"
>> WHERE type = "project" AND status = "active"
>> ```
>
>> [!focus] Focus Today
>> ![[Focus#^focus]]





