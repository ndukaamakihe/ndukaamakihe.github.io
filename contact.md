---
title: Contact
permalink: /contact/
intro: "Simple ways for people to get in touch or learn more about my work."
---
## Contact

- Email: [{{ site.data.profile.email }}](mailto:{{ site.data.profile.email }})
- LinkedIn: [View profile]({{ site.data.profile.social.linkedin }})

{% if site.data.profile.social.github != "" %}
- GitHub: [View profile]({{ site.data.profile.social.github }})
{% else %}
- GitHub: Add your GitHub URL in `_data/profile.yml`
{% endif %}

## CV

Use the button on the homepage to download my CV as a PDF. When I update my resume, the file at `assets/files/cv.pdf` can be replaced with the latest version.
