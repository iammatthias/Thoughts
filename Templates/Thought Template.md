---
<%*
let title = tp.file.title
if (title) {
    title = tp.file.creation_date("YYYYMMDD-HHmm");
    await tp.file.rename(`${title}`);
} %>
date: "<% tp.file.creation_date("YYYY MM DD") %>"
time: "<% tp.file.creation_date("HH:mm") %>"
published: false

---

