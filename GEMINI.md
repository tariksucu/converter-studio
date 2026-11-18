# Converter Studio

This extension connects the Converter Studio MCP server (https://converter.studio/api/mcp), which converts files between 67 formats: video, audio, images, PDFs, documents, e-books, subtitles, data and archives.

- Use `list_formats` to check a conversion, then `convert` with a `url`, a small file as `contentBase64` + `fileName`, or an `uploadId` from `create_upload` for bigger local files.
- Results are download links valid for 6 hours.
- Conversions use credits from the user's converter.studio account; ask before confirming one above `maxCredits` (`confirm_conversion`).
- Set your API key with `gemini extensions config converter-studio` (create one at https://converter.studio/account#api-keys).
