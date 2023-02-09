# Wednesday Team Meeting - <%= date.toFormat("MMMM d, yyyy") %>

## Attendance

- [ ] Hassan Sani, @inidaname
- [ ] Ibrahim, @hallydon
- [ ] Kelvin, @KelvinthePM
- [ ] Godsent @DataDeus
- [ ] Akim @keemzyddev
- [ ] Emmanuel @Odenfedy
- [ ] Abu Madi @mxhdiqaim
- [ ] Umar @prexidential

...

## Agenda

Extracted from **<%= agendaLabel %>** labelled issues and pull requests from **<%= owner %>/<%= repo %>** prior to the meeting.

<%= agendaIssues.map((i) => {
  return `* ${i.title} [#${i.number}](${i.html_url})`
}).join('\n') %>

## Action Items


## Notes
Other issues from other repos maybe added to the comment
## Chat
