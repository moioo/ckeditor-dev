@bender-ui: collapsed
@bender-tags: 2858, 4.11.4, bug
@bender-ckeditor-plugins: wysiwygarea, language, contextmenu, clipboard, toolbar

## Procedure

1. Open console.
2. Open editor's context menu.
3. Right click any menu item.

	### Expected result:

	Focus is moved to the clicked item.

	### Unexpected result:

	Action connected with clicked item is applied to the editor.
4. Press `Space`/`Enter`.

	### Expected result:

	Action connected with clicked item is applied to the editor.

	### Unexpected result:

	Error is thrown.

Repeat the procedure for the menu under "Language" button.