# Tenax support site

This is a plain static site for GitHub Pages. It has no build step or dependencies.

## Publish with GitHub Pages

1. Create a GitHub repository and put the contents of this folder in the repository root.
2. Open the repository's **Settings > Pages**.
3. Choose **Deploy from a branch**, select the default branch, and select **/ (root)**.
4. Use the resulting `https://<username>.github.io/<repository>/` URL as the support URL in App Store Connect.
5. Use the same URL with `privacy.html` appended as the privacy policy URL.

The pages intentionally use relative links, so they work both from a repository path and from a custom domain.
