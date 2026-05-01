# Google Chat API

The Google Chat API enables building Chat apps that integrate with Google Chat. It provides RESTful access to manage Chat spaces, memberships, messages, reactions, attachments, and custom emojis. The API supports creating conversational bots, automating messaging workflows, and managing organizational chat resources programmatically.

## Base URL

```
https://chat.googleapis.com
```

## Resources

The Google Chat API v1 provides the following resources:

- **Spaces** - Create, list, update, delete, search, and set up chat spaces
- **Members** - Manage space memberships
- **Messages** - Create, read, update, and delete messages
- **Reactions** - Add and remove reactions on messages
- **Attachments** - Upload and download media attachments
- **Custom Emojis** - Create and manage custom emoji
- **Space Events** - Track events within spaces
- **User Sections** - Organize spaces into sections
- **Read State** - Track and update read state for spaces and threads

## Artifacts

| Artifact | Path |
|----------|------|
| APIs.yml | [apis.yml](apis.yml) |
| OpenAPI 3.1.0 | [openapi/openapi.yml](openapi/openapi.yml) |
| JSON Schema (Draft 2020-12) | [json-schema/json-schema.yml](json-schema/json-schema.yml) |
| JSON-LD Context | [json-ld/json-ld.jsonld](json-ld/json-ld.jsonld) |

## Documentation

- [Chat API Guide](https://developers.google.com/workspace/chat/api/guides)
- [REST API Reference](https://developers.google.com/workspace/chat/api/reference/rest)

## Maintainers

- **Kin Lane** - kin@apievangelist.com

_Last updated: 2026-04-28_
