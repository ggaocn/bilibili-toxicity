This repository contains a Bilibili dataset sourced from 10 content domains. Given the constraint of comment volume, the collection strategy prioritized one or two representative uploaders from each domain, yielding a total of 18 uploaders.

Repository File Description
├──  SQL Backup Files
│   ├── cmt.sql
│   │   └── Comments table backup: stores main comments made by users on videos
│   ├── subcmt.sql
│   │   └── Sub-comments table backup: stores replies to main comments
│   ├── videoinfo.sql
│   │   └── Video information table backup: stores video metadata such as title, intro, play(view count), etc.
│   └── user.sql
│       └── Uploader table backup: stores user information of video uploaders
│
└──  Table Creation Script
    └── create_table.txt
        └── Table creation script: contains CREATE TABLE statements and field descriptions for all 4 tables above
