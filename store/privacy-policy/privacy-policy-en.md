# Privacy Policy — Hilitely

**Last updated:** 8 November 2026

This policy describes how the Chrome and Firefox extension **Hilitely** ("the Extension") handles information.

## Who provides the Extension

The Extension is published by **PeterShift**.
Contact: **petershift.dev@gmail.com**

## What the Extension does

On a site you switch on, the Extension highlights a passage you select and finds that highlight again after a reload or a change to the page, by the words rather than by their place in the layout. Notes, tags, and a library of quotes stay on this computer.

## What the Extension stores

When you highlight text, the Extension saves a record on your computer:

- the quoted text and about 100 characters before and after it, so the highlight can be found again;
- the page address, its canonical address if the page declares one, and the page title;
- the color, and any note or tags you type;
- when the highlight was created and changed, and whether it was found on the page the last time.

Settings stay on this computer too: the last color you picked, whether the cursor goes to the note field, how the library sorts sites, and which enabled sites you switched off.

## Where it goes

Nowhere. Highlights stay in the browser, in the Extension's own database on this computer. The Extension has no server, no account, and no analytics. The Extension makes no network requests. We never receive your highlights, notes, or the addresses of the pages you read.

## Which sites it can read

The Extension does not ask to read every site. It runs only on sites you switch on from the toolbar icon, one site at a time, through the browser's own permission dialog. In Chrome, a host on a non-standard port is a separate site. In Firefox, permission for a host covers that host on any port. Until you do, it adds nothing to the page.

Switching a site off pauses it. Highlights disappear from that site's open tabs, and the script does not start there again until you switch it back on. The browser's permission stays, so turning it back on does not ask a second time. "Remove access to this site" takes the permission away. The next time you switch that site on, the browser asks again. Saved quotes stay in the library either way.

## Backups

A backup file is created only when you choose Download backup. It is saved where your browser saves downloads. Importing a backup reads a file you choose. Neither is uploaded anywhere.

## Deleting your data

Delete a highlight from the page or from the library, or use Delete all on this site in the library. Removing the Extension deletes all of its local data with the browser's usual cleanup.

## Permissions

| Permission | Why it is requested |
| --- | --- |
| `storage` | Saves settings on this computer: the last highlight color, whether the cursor goes to the note field, which enabled sites you switched off, and how the library sorts sites. Saved quotes are kept in the Extension's own database; this permission is not what stores them. |
| `activeTab` | When you click the toolbar icon, the popup reads the current tab's address to show the switch for that site and to step through the highlights on that page. |
| `scripting` | Starts the highlighter in the current tab right after you switch the site on, and in tabs of that site that are already open, so the page does not have to be reloaded. Removes the highlights from those tabs when you switch the site off. |
| Host access | Not granted at install. The browser asks for one site at a time, the first time you switch that site on. In Chrome, a host on a non-standard port is a separate site. In Firefox, permission for a host covers that host on any port. The highlighter runs only on sites you allowed and have not switched off. Switching a site off stops it there and keeps the permission. "Remove access to this site" removes it. |

## Remote code

The Extension runs only the local files shipped in the package. It does not download or execute remote JavaScript.

## Limited Use

The data is used only to show your highlights again and to list them in your library. It is not sold, not transferred to anyone, not used for advertising or to judge creditworthiness, and no person reads it. The use of this information complies with the Chrome Web Store User Data Policy (https://developer.chrome.com/docs/webstore/program-policies/limited-use), including the Limited Use requirements.

## Changes

If a later version starts sending data anywhere, this policy will say so before that version ships, and the Extension will ask you first.

## Contact

Questions about this policy: **petershift.dev@gmail.com**
