# Copy to Canvas Privacy Policy

Effective date: October 8, 2026

Copy to Canvas creates a static, editable copy of the web page selected by the user and places that copy on the user's clipboard for pasting into a Claude Design canvas.

## Data the extension handles

When the user clicks **Copy this page**, the extension temporarily processes the content and resources of the active page. This may include its URL and title, visible text, links, images, stylesheets, fonts, SVG artwork, and accessible embedded-frame content. A page may contain personal or sensitive information that is already visible to the user.

The extension removes scripts, event handlers, hidden inputs, passwords, and typed form values from the generated copy. This cleanup reduces accidental exposure but is not anonymisation; ordinary visible page content may still identify a person or reveal private information.

## How the data is used

The data is used only to create the clipboard copy requested by the user. The extension does not use it for advertising, analytics, profiling, credit decisions, or any unrelated purpose.

The extension may request page resources such as stylesheets, images, and fonts from their original HTTPS locations so that they can be included in the copy. Those requests are made to the original resource hosts and may be subject to their privacy policies.

## Storage, sharing, and retention

The developer does not receive or store captured page content. The extension does not upload the captured page to a developer-operated server and does not sell user data.

The generated copy is written to the user's system clipboard. It remains there until the clipboard is replaced or cleared. If the user pastes the copy into Claude Design or another destination, that destination receives the pasted content at the user's direction and handles it under its own terms and privacy policy.

## Permissions

- `activeTab` lets the extension read the current tab only after the user invokes it.
- `scripting` lets the extension create the requested static snapshot.
- `clipboardWrite` lets the extension place the finished artboard on the clipboard.
- Host access lets the extension retrieve page resources, including resources hosted on other domains.

The extension runs only code included in its installed package. It does not load remote executable code.

## Limited use

The extension's handling of user data is limited to providing its single, user-facing copy-to-canvas function. The use of information received from Google APIs adheres to the Chrome Web Store User Data Policy, including the Limited Use requirements.

## Changes and contact

This policy will be updated if the extension's data practices change. Questions can be sent through the support contact provided on the extension's Chrome Web Store listing.
