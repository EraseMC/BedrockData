# Bedrock 1.19 historical assets

The 27 versioned files ending in `-1.19.*` were restored on the `feature/legacy-1.19` branch from the parent tree of commit `285cdbb07a8fb188972e9564bf2b9ece11670452` in this repository. The files are unmodified captures, not regenerated from a newer Bedrock release.

The set comprises six `canonical_block_states` NBT files, six `block_state_meta_map` JSON files, six `block_id_to_item_id_map` JSON files, six `required_item_list` JSON files, and three `r12_to_current_block_map` binary files.

To verify any restored file, compare `git rev-parse '285cdbb07a8fb188972e9564bf2b9ece11670452^:<filename>'` with `git hash-object -- <filename>`. All 27 object IDs matched at restoration time. Keep future edits separate from these source captures and record the source of any additional 1.19 asset.
