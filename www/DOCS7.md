# Medusa documentation for Docs7

The `www/docs7` directory is a standalone Docs7 documentation project. It contains
the converted pages, navigation, images, and local Admin and Store OpenAPI
specifications. No Medusa application build or conversion command is required.

Use these settings when you add the repository to Docs7:

- Repository: `enesgules/medusa`
- Branch: `codex/docs7`
- Documentation directory: `www/docs7`

The content was converted from upstream commit
`0d514437c983ef855c3b0aaaf7c39c17b0412991` on September 8, 2026. Edit the files in
`www/docs7` directly.

The project includes Learn, Resources, User Guide, UI, Cloud, and the Admin and
Store API references. Resources use a section selector to keep pages small.
Imported MDX sections are included in their parent pages.
API pages use code examples and linked schema definitions. The full OpenAPI
files are included in `www/docs7/openapi`. UI examples are provided as source code. Reference diagrams are provided as
ordered step descriptions. Cloud pricing links to Medusa's current pricing page.

Reference page names omit dots, as required by Docs7. Internal links use the new
page names. Section links with no matching section open the target page.
The conversion does not include Medusa's application servers, live
component previews, or external services.

`llms-full.txt` contains the written guides and stays below the upload limit.
The generated `llms.txt` index and individual `.md` URLs include the API and type
references. Update the text export if you edit the guide content.
