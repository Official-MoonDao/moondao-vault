<%*  
const dv = app.plugins.plugins["dataview"].api;  
const query = 'TABLE WITHOUT ID file.link as Term, Definition, Related, aliases as AKA FROM "MoonDAO/reference/Glossary" and -"MoonDAO/templates" SORT file.name ASC';  
let out = await dv.queryMarkdown(query)
tR += out.value
%>