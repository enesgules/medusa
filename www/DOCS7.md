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
Store API references. Resources use Docs7 product groups. Each module or reference has its own sidebar.
The selector lists only the items in its group. Page-count batches are not used.
Imported MDX sections are included in their parent pages.
The home page uses Docs7 cards, tabs, and a copyable AI prompt. The icon catalog
uses the original SVG artwork and Docs7 copy controls. Color samples use Docs7's
light and dark values and copy the displayed color value.

API and schema pages use Docs7's OpenAPI renderer. The source files are in
`www/docs7/openapi`. Page URLs stay the same. Links in the specifications point
to the converted pages. The request playground is disabled.

UI examples include their source code and links to the official live examples.
Workflow diagrams use Mermaid and the stages in the original workflow data.
The linked step descriptions remain below each diagram. Cloud pricing links to
Medusa's current pricing page.

Reference page names omit dots, as required by Docs7. Internal links use the new
page names. Section links with no matching section open the target page.
The conversion does not include Medusa's application servers, live
component previews, or external services.

`llms-full.txt` contains the written guides and stays below the upload limit.
The generated `llms.txt` index and individual `.md` URLs include the API and type
references. Update the text export if you edit the guide content.
