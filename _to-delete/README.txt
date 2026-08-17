Orphaned image files — safe to delete.

None of these are referenced by quiz-data.json. They are leftovers from
photo swaps: the editor saved a .webp, the entry later moved to a different
file, and the old one stayed behind.

Moved here rather than deleted outright so you can confirm before they go.
Delete the whole folder when you are happy, or run:
    git rm -r images/_to-delete
