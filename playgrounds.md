# Playgrounds

What do I mean by playgrounds? 

A playground is a safe place to test and try new things, either from my own ideas or from courses I am taking on the topic.

All the playground Repos, follow the same naming structure: `playground-[topic]` they also all contain a formated readme.md file which acts as an index to the playground and is also structured:

````
# Playground for [topic]

A place to learn more about [topic], and try things.

## Notes

- [ ] [course-title; author](link)
- [x] [course-title; author](link) *last updated: ##/##/##*

## Projects

- [ ] project-title (file-path)
- [ ] [course-title; author](notes-link) project-title (file-path)
- [ ] [course-title; author](notes-link) [projects](link)
- [x] project-title (file-path) *last updated: ##/##/##*

## Resources

- [ ] [title](link)
- [x] [title](link) *last review: ##/##/##*
````

**Notes** are stored in a `notes` directory, and the general naming convention would be`notes/course-title--author.md` 
IF a course has a project to complete these will be linked to BUT stored within the `projects` directory such as `projects/course-title--author/project/` 

**Projects** are stored in a `projects` directory,
IF a course has multiple projects, then a *projects link* will be used in the main `README.md` file, to link to a course projects index `README.md` file within the projects directory `projects/course-title--author/README.md` and this will store all the projects created in the course.

**Resources** are links I have collected over time, a last reviewed date will be present if I have looked over all of the content contained from within the link.

**Checkmarks** are used for Notes, Projects and Resources; as away to see what is completed. IF Notes/Projects are complete they will have a last updated date, IF a Rsource is marked as completed it will have a last reviewed date.