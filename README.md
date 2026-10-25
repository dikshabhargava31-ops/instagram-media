# instagram-media

Photos and videos for scheduled Instagram posts. Instagram only downloads media from a public link, so the files live here and not in `claude-and-db`.

- **Adding files:** the [Instagram Planner](https://dikshabhargava31-ops.github.io/claude-and-db/schedule/) uploads here when you create a post. Claude Code adds files with `instagram/prepare_media.py` from `claude-and-db`.
- **Layout:** `media/YYYY-MM/` holds the files, one per post item. Each video has a `.poster.jpg` beside it for the planner's thumbnails.
- **Deleting:** a post's files must stay until it has been published. After that, they can be deleted.
