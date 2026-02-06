# How to Create the First Asset Release

## For Repository Maintainers

The GitHub Actions workflow is now configured and ready to automatically create asset releases. Here's how to trigger it:

## Method 1: Create a Version Tag (Recommended)

To create an official versioned release:

```bash
# Create and push a version tag
git tag v0.8.11
git push origin v0.8.11
```

This will automatically:
1. Trigger the GitHub Actions workflow
2. Create three ZIP archives of the assets
3. Publish them to the GitHub Releases page
4. Generate bilingual release notes

## Method 2: Manual Trigger

You can also manually trigger the workflow from the GitHub Actions tab:

1. Go to: https://github.com/DiamantTh/pokewilds-assets/actions
2. Click on "Create Asset Release" workflow
3. Click "Run workflow" button
4. Select the branch and click "Run workflow"

Note: Manual triggers will use "latest" as the version name.

## What Gets Created

The workflow creates three archive types:

1. **pokewilds-assets-complete-v*.zip** (~540 MB)
   - All assets including documentation and music
   
2. **pokewilds-assets-no-music-v*.zip** (~440 MB)
   - All assets except the music folder
   
3. **pokewilds-assets-v*.zip** (~440 MB)
   - Core game assets only (no docs, no music)

## After Release

Once published, users can download the assets from:
- https://github.com/DiamantTh/pokewilds-assets/releases

The README.md and DOWNLOAD.md already include links to the releases page.

## Future Releases

For future releases, simply create a new version tag:

```bash
git tag v0.8.12
git push origin v0.8.12
```

The workflow will automatically create and publish the new release.

## Verifying the Workflow

You can check the workflow status at:
https://github.com/DiamantTh/pokewilds-assets/actions

## Testing Without Publishing

To test the workflow without creating a public release, you can:
1. Fork the repository to your own account
2. Push a test tag there
3. Verify the archives are created correctly
4. Delete the test release and tag

## Notes

- The workflow requires the `GITHUB_TOKEN` which is automatically provided by GitHub Actions
- No additional secrets or configuration needed
- The workflow runs on Ubuntu and uses standard `zip` command
- Archives exclude `.git` and `.github` directories to save space
