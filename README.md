# Resume Attributes Specification

## Standard attributes
   - contact info: contact.first_name, contact.last_name, etc.
   - objectives
   - summary
   - education
   - work experience
    - *automatic statistics
      - GitHub repositories (stars, downloads, commits)
      - Drupal.org projects (downloads, commits)
   - volunteer experience
   - additional skills
   - skill levels
   - *work preferences
     - contract, part-time, full-time
     - in-office, telecommuniting
     - hourly rate / salary range
   - *security clearance levels
   - *affiliations
   - *certifications
     - A+, Cisco, etc.
     - driver's license
   - publications
   - awards
   - *patents
   - *portfolio
   - interests
   - references
   - languages
     - spoken
     - written
     - proficiency
   - picture
   - profiles
     - youtube, github, etc.

`*` attributes not found in [jsonresume](http://jsonresume.org/schema) schema.

## Standard variable types
   - string: UTF-8
   - date: ISO 8601:2004
   - skill level: `{skill: "my skill", percent: "80"}`
   - links: `[My portfolio](http://example.com)`

# Existing solutions
- [jsonresume](http://jsonresume.org)
- [Markdown Resume](http://there4development.com/markdown-resume)
- [Microformats](http://microformats.org/wiki/resume-formats)
- [HR-XML](http://www.hropenstandards.org)
