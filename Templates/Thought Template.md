---<%* let title = tp.file.title
if (title) {
    title = tp.file.creation_date("YYYYMMDD-HHmm");
    await tp.file.rename(`${title}`);
} %>
title: "<% tp.file.creation_date("YYYYMMDD-HHmm") %>"
date: "<% tp.file.creation_date("YYYY MM DD") %>"
time: "<% tp.file.creation_date("HH:mm") %>"
published: false
---

